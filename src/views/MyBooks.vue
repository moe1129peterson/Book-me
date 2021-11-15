<template>
    <NavBar/>
    <div>
       <h2>My Books</h2>
       <select id="filterCategory" class="categoryPicker">
          <option selected>Filter By Category</option>
        </select>
    </div>
</template>

<script>
import NavBar from '../components/utilities/Nav.vue'
export default {
    name: 'About', 
    components: {
        NavBar
    }
}

// const filterList = (event) => {
//   let selectElement = event.target;
//   let value = selectElement.value;
//   let filteredList = toggleReadLater.filter(e => e.toggleReadLater == value) || let filteredList = toggleHaveRead.filter(e => e.toggleHaveRead == value)
// }
// const categoryDropDown = document.getElementById('filterCategory');

</script>

<style>
</style>