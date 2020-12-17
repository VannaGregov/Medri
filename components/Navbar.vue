<template>
 <nav class="navbar d-flex justify-content-between px-5 position-fixed w-100 navbar-custom">
    <a class="navbar-brand" href="#"><img src="/images/medri-logo.svg" alt="MEDRI" /></a>
            <div class="position-relative">
        <a @click="isOpen = !isOpen">
            <div class="cyrcle">
                <img src="/icons/pills.png" alt="Pill" />
            </div>
        </a>
        <transition name="fade">
            <div
                class="position-absolute  subnav d-flex flex-column justify-content-center mt-1"
                v-if="isOpen"
            >
                <a class="pointer-container ">
                    <div class="position-relative">
                        <div class="position-absolute label01">
                            <p class="cyrcle-label">Help</p>
                        </div>
                        <div class="cyrcle cyrcle_small">
                            <img
                                src="icons/help.png"
                                alt="Help"
                            />
                        </div>
                    </div>
                </a>
                <a class="mt-2 pointer-container">
                    <a class="position-relative"     data-toggle="modal" data-target="#logoutModal">
                        <div class="position-absolute cyrcle-label label02">
                            <p class="cyrcle-label">Logout</p>
                        </div>
​
                        <div class="cyrcle cyrcle_small">
                            <img src="icons/logout.png" alt="Help" />
                        </div>
                    </a>
                </a>
            </div>
        </transition>
    </div>
 </nav>
</template>
<script>
export default {
     data() {
        return {
            isOpen: false
        };
    }

}
</script>
<style scoped>
.img-logo {
    width: 133px;
}
.cyrcle {
    width: 56px;
    height: 56px;
    background: #ffffff;
    border-radius: 100%;
    -webkit-box-shadow: 4px 4px 10px -6px rgba(0, 0, 0, 0.61);
    box-shadow: 4px 4px 10px -6px rgba(0, 0, 0, 0.61);
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}
.cyrcle_small {
    width: 42px;
    height: 42px;
}
.subnav {
    top: 65px;
    margin-left: 8px;
}
.fade-enter-active,
.fade-leave-active {
    transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
    opacity: 0;
}
​
.label01 {
    top: 8px;
    left: -50px;
}
.label02 {
    top: 8px;
    left: -67px;
}
​
.pointer-container {
    cursor: pointer;
}
.navbar-custom {
    top: 30px;
    z-index: 9999;
}
</style>