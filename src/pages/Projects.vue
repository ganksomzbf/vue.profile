<template>
    <div>
        <Navbar />
        <section class="projects">
            <h1 class="heading"> <span>my</span> projects </h1>
            <h3>{{project_name}}</h3>
            <p>{{project_detail}}</p>
            <div class="box-container">
                <iframe width="720" height="405" src="https://www.youtube.com/embed/603Hc7ycIS0"
                    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; 
            gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
        return {
            project_name: 'LAZ1',
            project_detail: '5 ตัวท็อปจากรายการเฟ้นหาไอดอลชื่อดัง LAZ iCON สู่การเดบิวต์เป็นศิลปินบอยกรุ๊ปน้องใหม่มาแรง LAZ1 พร้อมมาเขย่าวงการ T-Pop ด้วยซิงเกิลแรก Taste Me ที่ส่งมาให้แฟนคลับได้ลิ้มลองความรักในแบบฉบับของพวกเขา',
        }
    }
}
</script>

<style>

</style>