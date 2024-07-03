<template>
  <div class="container">
    <h1>Bootstrap dark theme</h1>
    <p>Настраиваемые стили для темной темы Bootstrap</p>

    <button class="btn btn-dark">Dark</button>
  </div>
</template>

<script>
import Button from "./components/Button.vue";
import ButtonGroup from "./components/ButtonGroup.vue";
import Input from "./components/Input.vue";
import InputGroup from "./components/InputGroup.vue";
import ListGroup from "./components/ListGroup.vue";

export default {
  components: {
    Button,
    ButtonGroup,
    Input,
    InputGroup,
    ListGroup,
  },
};
</script>