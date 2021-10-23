<template>
  <div class="center main-body">
    <div class="row">
        <div>
          <h3 class="center-horizontal">Enter some bytes</h3>
          <b-form-textarea
            class="ascii-input"
            id="textarea"
            v-model="text"
            placeholder="Enter something..."
            rows="8"
            max-rows="8"
          ></b-form-textarea>
          <h3 class="mt-3 mb-0"><span class="light-green">{{ bytesInTextArea }}</span> bytes in da box</h3>
        </div>
    </div>
    <div class="row mt-4">
            <b-alert variant="success" show>more tools coming soon -ozzie</b-alert>
    </div>
  </div>
</template>

<script>
export default {
  name: "DecimalToByte",
  data: function () {
    return {
      decimalInput: 0,
      text: "Enter text here",
    };
  },
  computed: {
    bytesInTextArea: function () {
      // character counter
      return this.text.length;
    },
  },
};
</script>


<style scoped>
.narrow {
    max-width: 960px;
}
.center {
  margin-left: auto;
  margin-right: auto;
}
.light-green {
    color: #42b983;
}
</style>