<template>
  <div id="home">
    <div class="name">
      <h1>ABDULAZEEZKEMP</h1>
      <h1>ABDULAZEEZKEMP</h1>
    </div>
    <div class="img">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni recusandae assumenda pariatur? Qui molestiae
      blanditiis cum, similique cumque ab animi, dolore inventore iusto, amet illo debitis ipsum quod delectus. Earum.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#home {
  width: 100%;
  height: 100%;
  background-color: rgb(248, 248, 170);
  display: flex;
  justify-content: center;
  align-items: end;
  flex-direction: column;
}

.name {
  font-size: 10rem;
  width: 180vw;
  height: 100vh;
  overflow-y: scroll;
  scroll-behavior: smooth;
  text-wrap: none;
  text-align: center;
  padding-top: 10%;
  display: flex;
}

.name::-webkit-scrollbar{
  display: none;
}

.name h1{
  animation: slider 10s infinite linear;
  font-family: 'Righteous', sans-serif;
}

@keyframes slider{
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-100%);
  }
}
</style>