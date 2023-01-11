<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="pb-4">

    <div class="d-none d-lg-flex w-100">
      <div class="bg-white" style="width: 35%;"></div>
      <div style="border-bottom: 40px solid #2A2C41;  border-left: 40px solid transparent;"></div>
      <div class="d-flex px-4 justify-content-end" style="width: 50%; background: #2A2C41;">
        <a class="btn btn-link text-danger" href=""><i class="bi bi-telephone-fill"><span class="px-2 text-light">(+254) 125 876 423</span></i></a>
        <a class="btn btn-link text-danger" href=""><i class="bi bi-envelope-fill"><span class="px-2 text-light">cmcmotors.com</span></i></a>
      </div>
      <div style="border-top: 40px solid #2A2C41;  border-right: 40px solid #EB1F1E;"></div>
      <div class="d-flex justify-content-center" style="width: 15%; background: #EB1F1E;">
        <a class="btn btn-link text-light" href=""><i class="fab fa-facebook-f"></i></a>
        <a class="btn btn-link text-light" href=""><i class="fab fa-twitter"></i></a>
        <a class="btn btn-link text-light" href=""><i class="fab fa-google"></i></a>
        <a class="btn btn-link text-light" href=""><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>

    <div class="d-none d-lg-flex w-100">
      <div class="d-flex align-items-center" style="width: 27%; background: #2A2C41;">
        <div class="p-2" style="background-color: #EB1F1E; background-image: linear-gradient(to right, #2A2C41 , #EB1F1E); width: 150px;"></div>
        <img src="./assets/img/cmc-logo.png" alt="" class="img-fluid" style="width: 80px;">
        <div class="dropdown bg-white text-dark">
          <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
            <img src="./assets/img/kenya.png" class="img-fluid" style="width: 30px;"><span class="px-2">Kenya</span>
          </button>
          <ul class="dropdown-menu">
            <li></li>
          </ul>
        </div>
      </div>
      <div style="border-bottom: 80px solid transparent;  border-left: 80px solid #2A2C41;"></div>
      <ul class="nav bg-white text-uppercase d-flex align-items-end justify-content-end" style="width: 50%;">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">get vehicle quote</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">shop for parts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">after sales</a>
        </li>
      </ul>
    </div>
    
  </header>
  
  <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="./assets/img/mazda_6.png" class="img-fluid d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="./assets/img/mazda_6.png" class="img-fluid d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="./assets/img/mazda_6.png" class="img-fluid d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<div class="py-5">
        <div class="container">
          <div class="container">
            <div class="">
              <div class="row text-uppercase text-center text-white pb-4">
                <div class="col-md-3 p-3" style="background:#1F1F37;">
                  <img src="./assets/img/car.png" alt="" class="img-fluid" style="width: 50px">
                  <h6 style="font-size:small;">saloon car</h6>
                </div>
                <div class="col-md-3 p-3" style="background:#F7F7F7;">
                  <img src="./assets/img/car_1.png" alt="" class="img-fluid" style="width: 50px">
                  <h6 style="font-size:small; color:#EB1F1E;">sports utility vehicle</h6>
                </div>
                <div class="col-md-2 p-3" style="background:#2A2C41;">
                  <img src="./assets/img/car_2.png" alt="" class="img-fluid" style="width: 50px">
                  <h6 style="font-size:small;">4*4</h6>
                </div>
                <div class="col-md-2 p-3" style="background:#1F1F37;">
                  <img src="./assets/img/car_3.png" alt="" class="img-fluid" style="width: 50px">
                  <h6 style="font-size:small;">tractors & agriculture</h6>
                </div>
                <div class="col-md-2 p-3" style="background:#2A2C41;">
                  <img src="./assets/img/car_4.png" alt="" class="img-fluid" style="width: 50px">
                  <h6 style="font-size:small;">trucks & heavy commercial</h6>
                </div>
              </div>
              <!-- <div class="row text-uppercase text-white mb-5 p-3" style="background:#1F1F37">
                <div class="col-md-6">
                  <div class="row">
                    <div class="col-md-6">
                      <h6 style="font-size:smaller; cursor: pointer;">sort by: <span style="text-decoration-line: underline; text-decoration-style: dotted; color:#EB1F1E;">date added</span><i class="bi bi-chevron-down"></i></h6>
                    </div>
                    <div class="col-md-6">
                      <h6 style="font-size:smaller; cursor: pointer;">view: <span style="text-decoration-line: underline; text-decoration-style: dotted; color:#EB1F1E;">10 per page</span><i class="bi bi-chevron-down"></i></h6>
                    </div>
                  </div>
                </div>
                <div class="col-md-6 px-5">
                  <img src="./assets/img/grid.png" alt="" class="img-fluid" style="width: 180px;">
                </div>
              </div> -->
          <div class="row">
            <div class="col-lg-3">
              <div class="card mb-4" style="">
                <div class="text-uppercase text-center p-2" style="background:#2A2C41;">
                  <h6 class="text-white">filter <span class="pb-5" style="color: #EB1F1E;">car</span></h6>
                </div>
                <div style="background: #ECF1F5;">
                  <div class="container-fluid">
                    <div class="my-2">
                      <label for="" style="font-weight: bold; font-size:small">MAKE</label>
                      <select class="form-select mb-3" aria-label="" style="font-weight: lighter; color: #ADB3B9;">
                        <option selected>Select Make</option>  
                      </select>
                    </div>
                    <div class="my-2">
                      <label for="" style="font-weight: bold; font-size:small">Model</label>
                      <select class="form-select mb-3" aria-label="" style="font-weight: lighter; color: #ADB3B9;">
                        <option selected>Select Model</option>  
                      </select>
                    </div>
                    <div class="my-2">
                      <label for="" style="font-weight: bold; font-size:small">Year</label>
                      <select class="form-select mb-3" aria-label="" style="font-weight: lighter; color: #ADB3B9;">
                        <option selected>Select Year</option>  
                      </select>
                    </div>
                    <div class="my-2">
                      <label for="" style="font-weight: bold; font-size:small">Colour</label>
                      <select class="form-select mb-4" aria-label="" style="font-weight: lighter; color: #ADB3B9;">
                        <option selected>Select Colour</option>  
                      </select>
                    </div>
                  </div>
                </div>
                <div style="background:#2A2C41 ;">
                  <div class="container-fluid py-2">
                    <h6 class="text-white">PRICE RANGE</h6>
                    <img src="./assets/img/bar.png" class="img-fluid">
                    <div class="d-flex justify-content-between" style="color:#EB1F1E;">
                      <h6>Ksh 1M</h6>
                      <h6>Ksh 8M</h6>
                    </div>
                  </div>
                </div>
              </div>
              <div class="card">
                <div style="background:#2A2C41; color: white;" class="p-2 text-center">
                  <h4>JANUARY SALE</h4>
                </div>
                <img src="./assets/img/mazda_4.png" alt="" class="img-fluid">
                <div style="background:#2A2C41; position: relative;" class="container-fluid text-white">
                  <span class="text-white h5 py-2" style="background: #EB1F1E; position: absolute; top: -6%; padding-left: 38px; padding-right: 38px;">Ksh 1,500,000</span>
                  <div class="pt-5 pb-3">
                    <p>ENGINE TYPE: <span style="font-size:medium;">Four Cylinder</span></p>
                    <p>TRANSMISSION: <span style="font-size:medium;">Automatic</span></p>
                    <p>FUEL TYPE: <span style="font-size:medium;">Petrol</span></p>
                    <p>VEHICLE ID: <span style="font-size:medium;">Qx8qx8imZ</span></p>

                  </div>
                  <button class="btn text-white w-100 mb-5" style="background:#EB1F1E;">GET QUOTE</button>
                </div>
              </div>
            </div>
            <div class="col-lg-9">
              <div class="row">
                <div class="col-lg-4">
                  <div class="card mb-5" style="border: 0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                  <div class="card mb-5" style="border: 0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                  <div class="card mb-5" style="border: 0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4">
                  <div class="card car mb-5" style="border: 0; box-shadow: 0 0 10px 0 #F0F0F0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                  <div class="card car mb-5" style="border: 0; box-shadow: 0 0 10px 0 #F0F0F0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                  <div class="card car mb-5" style="border: 0; box-shadow: 0 0 10px 0 #F0F0F0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4">
                  <div class="card mb-5" style="border: 0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                  <div class="card mb-5" style="border: 0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                  <div class="card mb-5" style="border: 0;">
                    <div class="container-fluid">
                      <div class="pt-5">
                        <img src="./assets/img/mazda_3.png" alt="" class="img-fluid">
                      </div>
                      <div class="pt-3">
                        <h6 style="font-size:small">MAZDA ATENZA 2014</h6>
                        <img src="./assets/img/stars.png" alt="" class="img-fluid" style="width: 70px;">
                        <p style="font-size: small; color:#ADB3B9; font-weight: bold;">Starting From <span style="color:#EB1F1E; font-size: small; font-weight: bold;">Ksh 1,400,000</span></p>
                      </div>
                      <div>
                          <p class="h6" style="font-size: small;">ENGINE TYPE: <span style="font-size:small; color: #ADB3B9;">Four Cylinder</span></p>
                          <p class="h6" style="font-size: small;">TRANSMISSION: <span style="font-size:small; color: #ADB3B9;">Automatic</span></p>
                          <p class="h6" style="font-size: small;">FUEL TYPE: <span style="font-size:small; color: #ADB3B9;">Petrol</span></p>
                          <p class="h6" style="font-size: small;">VEHICLE ID: <span style="font-size:small; color: #ADB3B9;">Qx8qx8imZ</span></p>
                      </div>
                    </div>
                    <div>
                      <button class="btn btn-sm w-50 text-white" style="background: #575A69;">DESCRIPTION</button>
                      <button class="btn btn-sm w-50 text-white" style="background: #EB1F1E;">GET QUOTE</button>
                    </div>
                  </div>
                </div>
                <div>
                  <nav aria-label="...">
                    <ul class="pagination">
                      <li class="page-item disabled">
                        <a class="page-link" href="#" tabindex="-1" aria-disabled="true">Previous</a>
                      </li>
                      <li class="page-item active"><a class="page-link" href="#">1</a></li>
                      <li class="page-item" aria-current="page">
                        <a class="page-link" href="#">2</a>
                      </li>
                      <li class="page-item"><a class="page-link" href="#">3</a></li>
                      <li class="page-item"><a class="page-link" href="#">4</a></li>
                      <li class="page-item"><a class="page-link" href="#">5</a></li>
                      <li class="page-item">
                        <a class="page-link" href="#">Next</a>
                      </li>
                    </ul>
                  </nav>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <footer>
        <div class="footer-top">
            <div class="container">
                <div class="container">
                  <div class="row">
                    <div class="col-md-5 pb-5" style="padding-right: 100px;">
                      <div class="pb-4">
                        <h5>Lorem ipsum</h5>
                        <p class="py-2" style="font-size:small; font-weight:lighter; color: #ADB3B9;">dolor sit amet consectetur adipisicing elit, sed do oiusmod tempor incididunt ut labore et dalore magna aliqua. Ut enim and minim veniam, quis nostrud</p>
                      </div>
                      <div>
                        <p class="pb-4"><a href="" style="font-weight:bolder;">READ MORE</a></p>
                        <div class="d-flex pb-3">
                          <input type="text" class="form-control" style="border-radius: 0 !important; position: relative;">
                          <p style="position: absolute; left: 5%; top: 15%; font-weight:400; color: #ADB3B9;">Subscribe on Updates</p>
                          <button class="btn" style="color: white; background: #EB1F1E;"><i class="bi bi-arrow-right"></i></button>
                        </div>
                        <span style="font-weight:lighter; font-size:smaller; color: #ADB3B9;">We guarantee that we will not share you email with any other party</span>
                      </div>
                    </div>
                    <div class="col-md-3 pb-5">
                      <div class="text-uppercase bold">
                        <h6>USEFUL <span class="bold" style="color: #EB1F1E;">links</span></h6>
                        <div class="row py-4" style="font-size:small;">
                          <div class="col-6">
                            <a href="">listings</a><br><br>
                            <a href="" style="color: #EB1F1E;">services</a><br><br>
                            <a href="">about</a><br><br>
                            <a href="">blog</a><br>
                          </div>
                          <div class="col-6">
                            <a href="">faq</a><br><br>
                            <a href="">link</a><br><br>
                            <a href="">shop</a><br><br>
                            <a href="">contacts</a><br>
                          </div>
                        </div>
                      </div>
                      <div style="border: 1px solid #ADB3B9; font-size: small;">
                        <div class="container">
                          <div class="pt-3 px-2">
                            <p>(+254) 123 456 789</p>
                            <p>enquires@cmcmotors.com</p>
                            <p>Nairobi Kenya</p>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-md-4 pb-5">
                      <div class="text-uppercase">
                        <h6>recent <span class="bold pb-5" style="color: #EB1F1E;">posts</span></h6>
                        <div>
                          <div class="d-flex align-items-center pb-5 pt-2">
                            <div>
                              <img src="./assets/img/mazda_2.png" class="img-fluid" style="width: 70px; border:1px solid #ADB3B9">
                            </div>
                            <div style="margin-left: 20px;">
                              <h6 style="font-size: small;">15 jan 2022</h6>
                              <h6><a href="" style="color:#EB1F1E;">the new mazda axela 2021</a></h6>
                            </div>
                          </div>
                          <div class="d-flex align-items-center pb-5">
                            <div>
                              <img src="./assets/img/mazda_2.png" class="img-fluid" style="width: 70px; border:1px solid #ADB3B9">
                            </div>
                            <div style="margin-left: 20px;">
                              <h6 style="font-size: small;">15 jan 2022</h6>
                              <h6><a href="" style="color:#EB1F1E;">the new mazda axela 2021</a></h6>
                            </div>
                          </div>
                          <div class="d-flex align-items-center pb-5">
                            <div>
                              <img src="./assets/img/mazda_2.png" class="img-fluid" style="width: 70px; border:1px solid #ADB3B9">
                            </div>
                            <div style="margin-left: 20px;">
                              <h6 style="font-size: small;">15 jan 2022</h6>
                              <h6><a href="" style="color:#EB1F1E;">the new mazda axela 2021</a></h6>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <!-- <div class="col-md-1"></div> -->
                  </div>
                </div>
            </div>
        </div>
        <div class="footer-bottom text-center">
            <p class="mb-0">Copyright &copy;Sepia. All rights Reserved. <span style="margin-right: 10px">Privacy Policy</span><span style="font-weight:lighter">|</span><span style="margin-left: 10px">Website by </span><a
                href="">www.sepia.co.ke</a>
            </p>
            <a class="btn btn-link text-light" href=""><i class="fab fa-facebook-f" style="border-radius: 50%; border: 1px solid white; padding: 6px"></i></a>
            <a class="btn btn-link text-light" href=""><i class="fab fa-twitter"></i></a>
            <a class="btn btn-link text-light" href=""><i class="fab fa-google"></i></a>
        </div>
    </footer>

  <RouterView />
</template>

<style scoped>
.btn-link{
  font-size: small;
}

.btn {
  border-radius: 0 !important;
}

a {
  text-decoration: none;
}

.nav-link {
  border: 1px solid #d8d8d8;
  margin-left: 10px;
  margin-right: 10px;
  color: #d8d8d8;
}

.active, .nav-link:hover{
  color: white;
  background: #EB1F1E;
}

footer {
    background: linear-gradient(0deg, #353648, #232230), #2F3140;;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

footer .footer-top {
    padding-top: 80px;
    padding-bottom: 40px;
}

.footer-bottom {
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    padding-bottom: 20px;
    padding-top: 20px;
}

.footer-bottom i {
  border-radius: 50%; border: 1px solid white; padding: 6px
}


footer p, footer h6, footer h5, footer span, footer a{
    color: #fff;
}

footer .social-icons a {
    width: 50px;
    height: 50px;
    font-size: 20px;
    margin-left: 4px;
    margin-right: 4px;
}

.bold p, .bold h6 .bold{
  font-weight: bolder;
}

.car{
  cursor: pointer;
  transition: .3s transform cubic-bezier(.155,1.105,.295,1.12),.3s box-shadow,.3s -webkit-transform cubic-bezier(.155,1.105,.295,1.12);
}

.car:hover {
  transform: scale(1.05);
}

.pagination > li > a
{
    background-color: white;
    color: #EB1F1E;
}

.pagination > li > a:focus,
.pagination > li > a:hover,
.pagination > li > span:focus,
.pagination > li > span:hover
{
    color: #EB1F1E;
    background-color: #eee;
    border-color: #ddd;
}

.pagination > .active > a
{
    color: white;
    background-color: #EB1F1E;
    border: solid 1px #EB1F1E;
}

.pagination > .active > a:hover
{
    background-color: #EB1F1E;
    border: solid 1px #EB1F1E;
}

  /* Extra small devices (phones, 600px and down) */
  @media only screen and (max-width: 600px) {
    .carousel-item img {
        height: 250px;
    }
}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    .carousel-item img {
        height: 300px;
    }
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .carousel-item img {
        height: 300px;
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    .carousel-item img {
        height: 450px;
    }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    .carousel-item img {
        height: 450px;
    }
    .carousel-col {
        padding-right: 30px;
    }
}
</style>
