<template>
  <VButton x="15%" y="40%" c="purple" o t="Button" L="link" s="medium"></VButton>
  <VButton x="15%" y="50%" c="purple"  t="Vue+" L="link" s="medium"></VButton>
  <VButton x="30%" y="40%" c="red" o t="Button" L="link" s="medium"></VButton>
  <VButton x="30%" y="50%" c="red"  t="Vue+" L="link" s="medium"></VButton>
  <VButton x="45%" y="40%" c="blue" o t="Button" L="link" s="medium"></VButton>
  <VButton x="45%" y="50%" c="blue"  t="Vue+" L="link" s="medium"></VButton>
  <VButton x="60%" y="40%" c="orange" o t="Button" L="link" s="medium"></VButton>
  <VButton x="60%" y="50%" c="orange"  t="Vue+" L="link" s="medium"></VButton>
  <VButton x="75%" y="40%" c="green" o t="Button" L="link" s="medium"></VButton>
  <VButton x="75%" y="50%" c="green"  t="Vue+" L="link" s="medium"></VButton>
  
  <VButton x="60%" y="3%" c="blue" o t="Projects" L="link" s="small"></VButton>
  <VButton x="70%" y="3%" c="blue" o t="About" L="link" s="small"></VButton>
  <VButton x="80%" y="3%" c="blue" o t="Tutorial" L="link" s="small"></VButton>
  <VButton x="90%" y="3%" c="blue"  t="Login" L="link" s="small"></VButton>
  
  <VButton x="40%" y="70%" c="green"  t="START" L="link" s="large"></VButton>
  
  <VInput x="20%" y="10%" c="blue" t="Email:" s="medium"></VInput>
  <VInput x="20%" y="20%" c="blue" t="Password:" s="medium" p></VInput>
  
  <VFeature y="100%" c="rgb(245,245,240)" side="right" mp="Effortless Vue Components" sp="Each component is designed to look good on any page, and has the perfect amount of customization to make them very easy to put on your website." i="vuejs.jpg"></VFeature>
</template>

<script>
import VButton from "./VButton.vue";
import VInput from "./VInput.vue";
import VFeature from "./VFeature.vue";
export default {
  components:{
	VButton,
	VInput,
	VFeature
  }
  
}
</script>

<style scoped>

</style>
