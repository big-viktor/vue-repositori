<template>
  <div class="container_button">
    {{ nameBtn }}
  </div>
</template>

<script>
export default {
  name: "Button",
  props: {
    nameBtn: String,
  },
};
</script>

<style scoped>
.container_button{
background: #000000;
box-shadow: -9px 10px 54px -7px rgba(0, 0, 0, 0.23);
border-radius: 14px;
padding: 14px 35px;
top: 97px;
font-family: Poppins;
font-style: normal;
font-weight: 600;
font-size: 22px;
line-height: 94.9%;
text-align: center;
color: #FFFFFF;
}

</style>
