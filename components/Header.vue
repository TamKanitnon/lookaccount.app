<template>
    <div>
        <div class="border border-dark d-flex justify-content-center align-items-center gap-5" style="height: 70px">
            <div>
                <i class="fa-solid fa-house"></i>
                <a href="#">หน้าแรก</a>
            </div>
            <div>
                <i class="fa-regular fa-circle-down"></i>
                <a href="#">รายรับ</a>
            </div>
            <div>
                <i class="fa-regular fa-circle-up"></i>
                <a href="#">รายจ่าย</a>
            </div>
            <div>
                <i class="fa-regular fa-address-book"></i>
                <a href="#">ผู้ติดต่อ</a>
            </div>
            <div>
                <i class="fa-brands fa-codepen"></i>
                <a href="#">สินค้า</a>
            </div>
            <div>
                <i class="fa-solid fa-file-invoice-dollar"></i>
                <a href="#">การเงิน</a>
            </div>
            <div>
                <i class="fa-solid fa-book"></i>
                <a href="#">บัญชี</a>
            </div>
            <div>
                <i class="fa-solid fa-file"></i>
                <a href="#">เอกสาร</a>
            </div>
            <div>
                <i class="fa-solid fa-gear"></i>
                <a href="#">ตั้งค่า</a>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
    a {
        text-decoration: none;
        color: black;
    }
    a:hover {
        text-decoration: underline;
    }
    i {
        margin-right: 10px;
        color: #378fd6;
        font-size: 18px;
    }
</style>