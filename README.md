# bootstraploginpage
This is a login page made by using Bootstrap.<br>
focus:.container, .row, .col, <br>

    <section class="container">
    <div class="row">
        <!--<div class="col-sm-3 col-md-5 col-lg-7 order-first">
            <img src="patrickstar.jpg" class="img-fluid img-thumbnail">
        </div>試著在登入頁面左邊加入圖片-->
        <div class="col-sm-9 col-md-7 col-lg-5 mx-auto">
            <div class="bg-light border-0 shadow rounded-3 my-5 p-4 p-sm-5"><!--外框-->
                <p class="text-center mb-5 fw-medium fs-3">ID@JAM</p><!--標題-->
                <form>
                    <!--信箱-->
                    <div class="form-group input-group mb-3"><!--包住span和input-->
                        <span class="input-group-text">
                            <i class="bi bi-envelope-fill"></i><!--做一個圖示-->
                        </span>
                        <input class="form-control" type="email" name="" placeholder="Email address">
                    </div>
                    <!--密碼-->
                    <div class="form-group input-group mb-3">
                        <span class="input-group-text">
                            <i class="bi bi-lock-fill"></i>
                        </span>
                        <input class="form-control" type="password" placeholder="Password">
                    </div>
                    <!--核取方塊-->
                    <div class="form-check mb-3">
                        <input class="form-check-input" type="checkbox" value="" id="passwordcheck"><!--方塊在左，文字在右-->
                        <label class="form-check-label" for="passwordcheck">記住密碼</label>
                    </div>
                    <!--登入鈕-->
                    <button class="btn btn-primary btn-login text-uppercase fw-bolder col-12" type="submit">Sign in</button>
                    <hr class="my-4">
                    <!--其他登入方式-->
                    <!--GOOGLE--><!--btn-secondary,hover時顯色-->
                    <button class="btn btn-secondary btn-google btn-login text-uppercase fw-bold mb-3 col-12" type="submit">
                        <i class="bi bi-google"></i> Sign in with Google
                    </button>
                    <!--twitter-->
                    <button class="btn btn-secondary btn-twitter btn-login text-uppercase fw-bold mb-3 col-12" type="submit">
                        <i class="bi bi-twitter"></i> Sign in with Twitter
                    </button>
                    <!--facebook-->
                    <button class="btn btn-secondary btn-facebook btn-login text-uppercase fw-bold mb-3 col-12" type="submit">
                        <i class="bi bi-facebook"></i> Sign in with Facebook
                    </button> 
                </form>
            </div>
        </div>
    </div>
    </section>
