<template>
    <div className='central-content'>
        <Avatar/>
        <div className='content'>
            <h1 className='tittle'>David Rusycki</h1>
            <p className='description'>
                Hello, iam a web developer focused
                in backend applications based in
                Brazil. I have a degree in
                information systems and am
                fascinated by technology.
            </p>
        </div>
    </div>
</template>

<script>
import Avatar from '@/components/avatar/Avatar.vue';

export default {
    name: 'Home',
    components: {
        Avatar,
    }
}
</script>

<style scoped>

.central-content {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 80%;
}

.content {
    margin-left: 2em;
}
</style>