<div class="circle">word</div>

<style>
.circle{
  background: red;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  line-height: 100px;
  text-align: center;
  color: white;

  position: fixed;
  top: calc(50vh - 50px);
  left: calc(50vw - 50px);
}
</style>

<script>
window.addEventListener("mousemove",function(event){
  document.getElementsByClassName("circle")[0].style.top = (event.clientY - 50) +"px";
  document.getElementsByClassName("circle")[0].style.left = (event.clientX - 50) +"px";
});
</script>
