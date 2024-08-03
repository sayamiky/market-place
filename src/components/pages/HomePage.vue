<template>
  <header
    class="container-fluid bg-white py-3 border-bottom position-sticky top-0 z-3"
  >
    <div class="container-md d-flex justify-content-between align-items-center">
      <img src="@/assets/Images/Logo.png" alt="Logo" />
      <div
        class="header__navvbar row justify-content-between align-items-center"
        style="width: 1200px"
      >
        <div class="col-9 py-0 d-none d-sm-block">
          <div
            class="header__searchbar input-group align-items-center border rounded"
          >
            <span class="px-2">
              <i class="fa-solid fa-magnifying-glass"></i>
            </span>
            <input
              type="text"
              name=""
              id=""
              class="form-control form-control border-0 rounded-end-pill"
              placeholder="Search for items"
            />
          </div>
        </div>
        <div class="col-5 d-block d-sm-none border-end text-end">
          <i class="fa-solid fa-magnifying-glass"></i>
        </div>
        <div
          class="col-6 col-sm-3 fw-semibold justify-content-evenly align-items-center"
        >
          <button type="button" class="btn btn-cat rounded">Login</button>
          <button type="button" class="btn btn-cat rounded">Sign Up</button>

          <div class="margin hstack gap-3 vr"></div>
          <button
            class="btn btn-drpdw"
            id="dropdownMenuButton1"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            <i class="fa-solid fa-chevron-down"></i> EN
          </button>
          <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
            <li><a class="dropdown-item" href="#">ID</a></li>
            <li><a class="dropdown-item" href="#">KOR</a></li>
            <li><a class="dropdown-item" href="#">DEUTSCH</a></li>
          </ul>
        </div>
      </div>
    </div>
  </header>
  <main>
    <div class="jumbotron d-flex align-items-center">
      <div class="col-1"></div>
      <div class="card" style="width: 18rem">
        <div class="card-body">
          <h5 class="card-title">Ready to declutter your closet</h5>
          <p class="btn btn-success mt-3">Shop now !</p>
        </div>
      </div>
    </div>
    <div class="album py-5 bg-body-tertiary">
      <div class="container">
        <div class="row">
          <div class="col">
            <h4 class="col-9">Popular Items</h4>
          </div>
          <div class="col text-end">
            <a href="product.html">See All</a>
          </div>
        </div>
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-6 g-6">
          <div class="col px-1">
            <div class="card shadow-sm">
              <img
                class="bd-placeholder-img card-img-top"
                width="100%"
                height="225"
                src="@/assets/Images/cr1.jpg"
                role="img"
                aria-label="Placeholder: Thumbnail"
                preserveAspectRatio="xMidYMid slice"
                focusable="false"
              />
              <div class="card-body">
                <p class="card-text">Vintage Chicago Cubs White Crewneck</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group">
                    <button type="button" class="btn btn-sm btn-drpdw">
                      S/M
                    </button>
                  </div>
                  <small class="text-body-secondary"
                    ><i class="fa fa-heart-o" aria-hidden="true"></i> 19</small
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col px-1">
            <div class="card shadow-sm">
              <img
                class="bd-placeholder-img card-img-top"
                width="100%"
                height="225"
                src="@/assets/Images/cr2.jpg"
                role="img"
                aria-label="Placeholder: Thumbnail"
                preserveAspectRatio="xMidYMid slice"
                focusable="false"
              />
              <div class="card-body">
                <p class="card-text">Vintage Chicago Cubs White Crewneck</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group">
                    <button type="button" class="btn btn-sm btn-drpdw">
                      S/M
                    </button>
                  </div>
                  <small class="text-body-secondary"
                    ><i class="fa fa-heart-o" aria-hidden="true"></i> 19</small
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col px-1">
            <div class="card shadow-sm">
              <img
                class="bd-placeholder-img card-img-top"
                width="100%"
                height="225"
                src="@/assets/Images/cr3.jpg"
                role="img"
                aria-label="Placeholder: Thumbnail"
                preserveAspectRatio="xMidYMid slice"
                focusable="false"
              />
              <div class="card-body">
                <p class="card-text">Vintage Chicago Cubs White Crewneck</p>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group">
                    <button type="button" class="btn btn-sm btn-drpdw">
                      S/M
                    </button>
                  </div>
                  <small class="text-body-secondary"
                    ><i class="fa fa-heart-o" aria-hidden="true"></i> 19</small
                  >
                </div>
              </div>
            </div>
          </div>
          <div
            class="col px-1 d-flex align-items-center justify-content-center border rounded btn btn-collection"
            width="100%"
          >
            <a class="text-align" href="product.html">See All Product</a>
          </div>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col">
            <h4 class="col-9 pt-5">Shop by brand</h4>
          </div>
          <div class="d-flex flex-wrap sm-3">
            <div class="pe-2 mb-2">
              <input
                type="checkbox"
                class="btn-check"
                id="btn-check-outlined"
              />
              <label class="btn btn-outline-secondary" for="btn-check-outlined">
                Vans
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                class="btn-check"
                name=""
                id="btn-check-2-outlined"
              />
              <label
                class="btn btn-outline-secondary"
                for="btn-check-2-outlined"
              >
                Bohoo
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-3-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-3-outlined"
                class="btn btn-outline-secondary"
              >
                Mango
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-4-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-4-outlined"
                class="btn btn-outline-secondary"
              >
                Reebok
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-5-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-5-outlined"
                class="btn btn-outline-secondary"
              >
                Converse
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                class="btn-check"
                id="btn-check-outlined"
              />
              <label class="btn btn-outline-secondary" for="btn-check-outlined">
                Sandro
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                class="btn-check"
                name=""
                id="btn-check-2-outlined"
              />
              <label
                class="btn btn-outline-secondary"
                for="btn-check-2-outlined"
              >
                Nike
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-3-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-3-outlined"
                class="btn btn-outline-secondary"
              >
                Adidas
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-4-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-4-outlined"
                class="btn btn-outline-secondary"
              >
                Dior
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-5-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-5-outlined"
                class="btn btn-outline-secondary"
              >
                Puma
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-5-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-5-outlined"
                class="btn btn-outline-secondary"
              >
                Zara
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-5-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-5-outlined"
                class="btn btn-outline-secondary"
              >
                Bershka
              </label>
            </div>
            <div class="px-2 mb-2">
              <input
                type="checkbox"
                name=""
                id="btn-check-5-outlined"
                class="btn-check"
              />
              <label
                for="btn-check-5-outlined"
                class="btn btn-outline-secondary"
              >
                American Eagle
              </label>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
