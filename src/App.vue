<template>
  <el-container>
    <div class="row">
      <div class="col-md-12">
        <img src="./assets/kaohsiung.jpeg" alt="kaohsiung" class="img-fluid  w-100" />
        <!-- <img src="https://i.imgur.com/vR7NOt7.jpeg" alt="kaohsiung" class="img-fluid  w-100" /> -->
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
        <nav class="navbar navbar-expand-lg navbar-dark bg-info">
            <div class="container-fluid">
            <a class="navbar-brand" href="#">高雄探索</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarColor01">
                <ul class="navbar-nav me-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="#">首頁
                    <span class="visually-hidden">(current)</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">參考文獻</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">同學作品</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">聯絡老師</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false">目前登入的使用者</a>
                    <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">Action</a>
                    <a class="dropdown-item" href="#">Another action</a>
                    <a class="dropdown-item" href="#">Something else here</a>
                    <div class="dropdown-divider"></div>
                    <a class="dropdown-item" href="#">Separated link</a>
                    </div>
                </li>
                </ul>
            </div>
            </div>
        </nav>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12 p-3">          
        <router-view></router-view>          
      </div>
    </div>
    <el-footer  class="my-3 p-4 pb-5 bg-dark text-white text-center">
      <p>CJHS &copy; 2022 高雄市立前鎮高中地理科</p>
    </el-footer>
  </el-container>
</template>

<script>
export default {
}
</script>

<style>

</style>