<template>
  <div>
    <c-pane>
      <c-link>default</c-link>
      <c-link class="primary">primary</c-link>
      <c-link class="warning">warning</c-link>
      <br>
      <c-link size="xlarge">xlarge</c-link>
      <c-link size="large">large</c-link>
      <c-link size="small">small</c-link>
      <c-link size="xsmall">xsmall</c-link>
    </c-pane>
  </div>
</template>

<script>
import CPane from 'platojs/components/core/pane'
import CLink from 'platojs/components/core/link'
import CSpinner from 'platojs/components/core/spinner'

export default {
  components: {
    CPane,
    CLink,
    CSpinner
  }
}
</script>
