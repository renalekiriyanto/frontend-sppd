<style scoped src="@/assets/css/login.css"></style>

<template>
    <main class="login-page d-flex align-items-center min-vh-100 py-3 py-md-0">
        <div class="container">
            <div class="card login-card">
                <div class="row">
                    <div class="card-body">
                        <div class="col-md-6">
                            <img :src="imageHeader" class="login-card-jpg" />
                            <p
                            class="text-white font-weight-medium text-start flex-grow align-self-end footer-link text-small">
                            &copy; Badan Keuangan Kota <a href="http://bukittinggikota.go.id/" target="_blank"
                                class="text-white">Bukittinggi</a>
                            </p>
                        </div>
                        <div class="col-md-6">
                            <h1>form</h1>
                        </div>
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
<style scoped src="@/assets/css/login.css"></style>
