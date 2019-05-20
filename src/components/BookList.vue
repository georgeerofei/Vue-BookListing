<template>
    <div>
        <h1>{{title}}</h1> 
        <ul>
            <li v-for="book in books">{{book.title}}:{{book.author}}</li>
        </ul>
    </div>
</template>



<script>
export default {
    name:"BookList",
    data() {
        return {
            title:"All Books",
            books:[
                {title:'Morometii', author:'George 1'},
                {title:'American Gods', author:'George 2'},
                {title:'Morometii 3', author:'George 3'}
            ]
        }
    }
}
</script>


<style>
    h1, h2{
        font-weight: normal
    }
    ul{
        list-style-type: none;
        padding: 0;
    }
</style>0  