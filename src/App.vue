<template>
  <div>
    <div id="main">
     <DomainList></DomainList>
    </div>
  </div>
</template>
      
<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from "./components/DomainList";
export default {
	name: "app",
	components:{
		DomainList
	}
};
</script>

<style>
#slogan {
  margin-top: 30px;
  margin-bottom: 30px;
}
#main {
  background-color: #f1f1f1;
  padding-top: 30px;
  padding-bottom: 30px;
}
</style>
