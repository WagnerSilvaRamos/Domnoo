<template>
    <footer>
        <div class="container">
            <div>
                <img :src="logoIcon"/>
                <div class="contact">
                    <div>Call Us</div>
                    <div>46872-7851</div>

                </div>
            </div>
        </div>

    </footer>

</template>

<script>

    import  Logo from '../../assets/images/logo.png';

    export  default {
        data() {
            return {
                logoIcon: Logo
                }
        }
    }
</script>

