<div class="svelte-centered-wrapper" style="{style}">
  <div class="svelte-centered-container" style="{innerStyle}">
    <slot></slot>
  </div>
</div>

<script>
  export default {
    data() {
      return {
        style: '',
        innerStyle: ''
      };
    }
  };
</script>
