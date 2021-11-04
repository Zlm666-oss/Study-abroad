<template>
    <router-view/>
</template>
<style lang="scss">
*{
    margin: 0;
    padding: 0;
}
li{
    list-style: none;
}
a{
    text-decoration: none;
}
img{
    border: none;
}
input,button{
    outline: none;
}
b,strong{
    font-weight: normal;
}
em,i{
    font-style: normal;
}
.clearfix::after{
    clear: both;
    display: block;
    content: "";
}

</style>
