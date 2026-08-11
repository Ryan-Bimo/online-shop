<template>
    <div class="container">
        <div class="kotak">
            <h1>Belanja alat gaul mu dengan mudah dan terpercaya</h1>
        <p>dari mulai bomber / jaket ? klik di bawah</p>
        <RouterLink to="/product">
            <button class="button">Belanja Sekarang</button>
        </RouterLink>
        </div>
    </div>
</template>

<style scoped>
/* .container{
    margin-top: 20px;
    justify-content: center;
    gap: 20px;
    background-color: #ebeef0;
    border-radius: 20px;
}
.card{
    
    width: 360px;
    height: 16rem;
    border-radius: 15px;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
    overflow: hidden;
    text-align: center;
} */
 .container {
  display: grid;
  place-content: center;
}

.kotak {
  width: 600px;
  height: 200px;
  background-color: rgb(111, 142, 238);
  border-radius: 15px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
  overflow: hidden;
  text-align: center;
}
.button {
            padding: 10px 15px;
            background: blue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
}
</style>