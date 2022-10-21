<script>
import BaseInput from '../components/BaseInput.vue';

export default {
    name: "TestView",
    data: () => ({
        title: "Test",
        //input
        input: {
            name: '',
            email: '',
            kelas: ''
        }
    }),
    components: { BaseInput }
}
</script>

<template>
    <div class="Test">
        <h1>{{ title }}</h1>
        <BaseInput v-model="input.name" name="name" label="Name" type="text" />
        <BaseInput v-model="input.email" name="email" label="Email" type="email" />
        <BaseInput for="class" label="Class" />
        <select v-model="input.class" name="class">
            <option value="Pilih Kelas" disabled>Pilih Kelas</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
        </select>
        <br>
        <BaseInput type="submit" v-on="click" value="Submit" label="Submit" />
    </div>
</template>

<style>
@media (min-width: 1024px) {
  .test {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
}
</style>