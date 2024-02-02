<template>
    <main class="login-page d-flex align-items-center min-vh-100 py-3 py-md-0">
        <div class="container">
            <div class="card rounded-lg">
                <div class="row">
                    <div class="col-sm-6 position-relative d-flex">
                        <img :src="imageHeader" class="logo-card-img rounded-start" />
                        <div class="overlay-text text-center">
                            <p class="text-white font-weight-medium footer-link text-small">
                                &copy; Badan Keuangan Kota <a href="http://bukittinggikota.go.id/" target="_blank" class="text-white">Bukittinggi</a>
                            </p>
                        </div>
                    </div>
                    <div class="col-sm-6 p-5">
                        <div class="row border-2">
                            <div class="col-auto p-2">
                                <img :src="logoFit" alt=""
                                    style="height: auto; width: 45px">
                            </div>
                            <div class="col text-center">
                                <span><b>SPPD</b><br>Sistem Pengelolaan Pendapatan Daerah</span><br>
                            </div>
                        </div>
                        <br>

                        <form action="" method="post">
                            <div class="form-group">
                                <label for="username" class="sr-only">Username</label>
                                <input type="text" name="username" id="username" class="form-control"
                                    placeholder="Username" required>
                            </div>
                            <div class="form-group mb-4">
                                <label for="password" class="sr-only">Password</label>
                                <input type="password" name="password" id="password" class="form-control"
                                    placeholder="***********" required>
                            </div>
                            <button type="submit" class="btn btn-block login-btn mb-4">Login</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
import imageHeader from '@/assets/image/home-header.webp'
import logoFit from '@/assets/image/bukittinggi-logo-fit.webp'

export default {
    name: 'Login',
    data() {
        return {
            imageHeader: imageHeader,
            logoFit: logoFit,
        }
    }
}
</script>

<style scoped src="../../../assets/css/login.css"></style>