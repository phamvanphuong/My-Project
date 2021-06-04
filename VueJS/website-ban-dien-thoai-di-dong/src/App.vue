<template>
  <div id="app">
    <Header />
    <hr>
    <Counter />
    <hr>
    <Message />
    <hr>
    <Click />
    <hr>
    <Model />
    <hr>
    <SeeTrueFalse />
    <hr>
    <Vfor />
    <hr>
    <Vbind />
    <hr>
    <Todos />
    <hr>
    <Raw />
    <hr>
    <a v-bind:[attributeName]="url">https://www.google.com/</a>
    <hr>
    <Array />
    <hr>
    <ArrayEx />
    <hr>
    <WatchExample />
    <hr>
    <Watch />
    <hr>
    <ClassEx />
    <hr>
    <Method />
    <hr>
    <EventMethod />
    <hr>
    <EventMethod1 />
    <hr>
    <EventMethod2 />
    <hr>
    <FormInputBindings />
    <hr>
    <FormInputBindingsCheckbox />
    <hr>
    <FormBindingsCheckNames />
    <hr>
    <FormBindingsRadio />
    <hr>
    <FormBindingsSelect />
    <hr>
    <FormBindingsSelectBoundToArray />
    <hr>
    <FormBindingsSelectRenderWithVfor />
    <hr>
   

  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Counter from "./components/Counter.vue"
import Message from "./components/Message.vue"
import Click from "./components/Click.vue"
import Model from "./components/Model.vue"
import SeeTrueFalse from "./components/SeeTrueFalse.vue"
import Vfor from "./components/Vfor.vue"
import Vbind from "./components/Vbind.vue"
import Todos from "./components/Todos.vue"
import Raw from "./components/Raw.vue"
import Array from "./components/Array.vue"
import ArrayEx from "./components/ArrayEx.vue"
import WatchExample from "./components/WatchExample.vue"
import Watch from "./components/Watch.vue"
import ClassEx from "./components/ClassEx.vue"
import Method from "./components/Method.vue"
import EventMethod from "./components/EventMethod.vue"
import EventMethod1 from "./components/EventMethod1.vue"
import EventMethod2 from "./components/EventMethod2.vue"
import FormInputBindings from "./components/FormInputBindings.vue"
import FormInputBindingsCheckbox from "./components/FormInputBindingsCheckbox.vue"
import FormBindingsCheckNames from "./components/FormBindingsCheckNames.vue"
import FormBindingsRadio from "./components/FormBindingsRadio.vue"
import FormBindingsSelect from "./components/FormBindingsSelect.vue"
import FormBindingsSelectBoundToArray from "./components/FormBindingsSelectBoundToArray.vue"
import FormBindingsSelectRenderWithVfor from "./components/FormBindingsSelectRenderWithVfor.vue"

// import MultipleBindingsVmodel from "./components/MultipleBindingsVmodel.vue"
export default {
  name: "App",
  components: {Header,Counter, Message, Click, Model, SeeTrueFalse, Vfor, Vbind, Todos, Raw, Array, ArrayEx, WatchExample,
   Watch, ClassEx, Method, EventMethod, EventMethod1, EventMethod2, FormInputBindings, FormInputBindingsCheckbox, 
   FormBindingsCheckNames, FormBindingsRadio, FormBindingsSelect, FormBindingsSelectBoundToArray, FormBindingsSelectRenderWithVfor, 
   }

};
</script>

<style>

</style>
