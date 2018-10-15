<template>
  <container>
  <row>
    <column col="4">
      <h5>{{msg}}</h5>
    </column>
    <column col="4">
      <h5>Column</h5>
    </column>
    <column col="4">
      <h5>Columns</h5>
    </column>
  </row>
  </container>
</template>

<script>
import { Container, Row, Column, mdbInput, MdTextarea, Btn, Fa, Modal, ModalHeader, ModalBody, ModalFooter } from 'mdbvue'
export default {
  name: 'HelloWorld',
  components: {
    Container,
    Row,
    Column,
    mdbInput,
    MdTextarea,
    Btn,
    Fa,
    Modal,
    ModalHeader,
    ModalBody,
    ModalFooter
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
