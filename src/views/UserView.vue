<template>


<div class="title">
     <h1>Liste des Utilisateurs</h1>
</div>


<div class="board">

     <button type="button" class="btn btn-info">
       <router-link class="link" to="/add-user">Add Users</router-link>
       </button>
     <br>
     <table class="table table-striped table-hover">
  <thead>
    <tr>
      <th scope="col">id</th>
      <th scope="col">name</th>
      <th scope="col">email</th>
      <th scope="col">password</th>
      <th scope="col">remember_token</th>
      <th scope="col">create_at</th>
      <th scope="col">update_at</th>
      <th scope="col">Actions</th>
      
      
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
      <td>@mdo</td>
      <td>@mdo</td>
      <td>@mdo</td>
      
     <td>
          <button type="button" class="btn btn-danger">Delete</button>
          <button type="button" class="btn btn-success">Edit</button>
      </td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
      <td>@mdo</td>
      <td>@mdo</td>
      <td>@mdo</td>
     
     <td>
          <button type="button" class="btn btn-danger">Delete</button>
          <button type="button" class="btn btn-success">Edit</button>
      </td>
    </tr>

    
  </tbody>
</table>

</div>
  
</template>

<script>

export default {
     components: {
          
     }
}

</script>
<style scoped>


 .table {
          margin: 4rem auto;
          max-width: 90rem;
          border-radius: 12px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
          padding: 7rem;
          background-color: #ffffff;
          font-family: 'Josefin Sans', sans-serif;
          font-family: 'Jost', sans-serif;
  }


ul,
      .link,
      .dropdown-item {
        font-weight: 500;
        color: #fff;
        list-style: none;
        text-decoration: none;
      }

.table td {
     padding: 2rem;
}
    .title {
          margin: 2rem;
          max-width: 90rem;
          text-align: center;
          padding: 1rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
     }

.board {
     padding: 5rem;
}



nav {
          background-color: #1461ac;
     }

 li {
        padding: 10px;
        margin-left: 25px;
        font-family: 'Josefin Sans', sans-serif;
        font-size: 20px;

}

#dropdown {
  text-align: right;
}



  
      .router-link,
      .dropdown-item {
        font-weight: 500;
        color: #fff;
        list-style: none;
        text-decoration: none;
      }

    
      .link,
      .dropdown-item {
        font-size: 14px;
        transition: .5s ease all;
        padding-bottom: px;
        border-bottom: 1px solid transparent;

      }

      
        .dropdown-item:hover {
          color: #fff;
          border-color: #EBD671;


        }


</style>
