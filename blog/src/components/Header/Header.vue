<template>
    <nav>
        <ul>
            <li><router-link to='/'>网站首页</router-link></li>
            <li><router-link to='/'>个人博客日记</router-link></li>
            <li><router-link to='/'>技术知识</router-link></li>
            <li><router-link to='/'>每日一笑</router-link></li>
            <li><router-link to='/'>洞见</router-link></li>
            <li><router-link to='/'>关于我</router-link></li>
            <li><router-link to='/'>留言</router-link></li>
        </ul>
    </nav>
</template>
<style lang="scss">
ul {
    list-style: none;
    text-align: center;
    margin: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #333333;
    text-decoration: none;
}
</style>
