<template>
  <div class="container">
    <div>
      <cld-image
        public-id="examples/avatar"
        width="900"
        height="900"
        crop="thumb"
        fetchFormat="auto"
        quality="auto"
        responsive
      />
    </div>
    <div>
      <cld-image public-id="examples/avatar">
        <cld-transformation width="100" height="100" crop="thumb" />
        <cld-transformation fetchFormat="auto" quality="auto" />
      </cld-image>
    </div>
  </div>
</template>