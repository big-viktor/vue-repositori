<template>
  <div class="container_white">
          {{ nameBtnWite }}
  </div>
</template>
<script>
export default {
  name: "Button",
  props: {
    nameBtnWite: String,
  },
};
</script>
<style whiteBtn>
.container_white{
    cursor: pointer;
    background: #FFFFFF;
padding: 15px 45px;
box-shadow: -9px 10px 54px -7px rgba(0, 0, 0, 0.23);
border-radius: 14px;
font-family: Poppins;
font-style: normal;
font-weight: 600;
font-size: 20px;
line-height: 94.9%;
text-align: center;
color: #000000;
}

</style>
