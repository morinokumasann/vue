<template>
    <div>
        <el-form ref="form" :model="form">
            <el-form-item label="アカウント">
                <el-input type="text" placeholder="アカウントを入力してください" v-model="form.name"></el-input>
            </el-form-item>
            <el-form-item label='パスワード'>
                <el-input type='password' placeholder="パスワードを入力してください" v-model="form.password"></el-input>
            </el-form-item>
        <el-form-item>
            <el-button type="primary" @click="onSubmit">登録</el-button>
        </el-form-item>
        </el-form>
    </div>
</template>

<script>
export default {
    name:'Login',
    data(){
        return{
            form:{
                name:'',
                password:''

            }

        }

    },
    methods:{
        onSubmit(){
            alert("Hello")

        }


    }


}
</script>

<style >

</style>