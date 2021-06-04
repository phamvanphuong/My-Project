<template>
    <div id="computed-basics">
        <p>Has published books:</p>
        <span>{{ publishedBooksMessage }}</span>
    </div>
</template>

<script>
export default {
    name: 'ArrayEx',
    data() {
    return {
      author: {
        name: 'John Doe',
        books: [
          'Vue 2 - Advanced Guide',
          'Vue 3 - Basic Guide',
          'Vue 4 - The Mystery'
        ]
      }
    }
  },
//   computed: {
//     // a computed getter
//     publishedBooksMessage() {
//       // `this` points to the vm instance
//       return this.author.books.length > 0 ? 'Yes' : 'No'
//     }
//   }
    computed: {
    fullName: {
    // getter
    get() {
      return this.firstName + ' ' + this.lastName
    },
    // setter
    set(newValue) {
      const names = newValue.split(' ')
      this.firstName = names[0]
      this.lastName = names[names.length - 1]
    }
  }
}
}
</script>

<style>

</style>