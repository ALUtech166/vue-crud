<template>

     <div class="title">
          <h1>DashBoard</h1>
     </div>
     
     <div class="visit-list">

           <h3>Progress Bar</h3>
          <br>

          <div class="progress">
               <div class="progress-bar bg-success" role="progressbar" style="width: 25%" aria-valuenow="25"
                    aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <br>
          <div class="progress">
               <div class="progress-bar bg-info" role="progressbar" style="width: 50%" aria-valuenow="50"
                    aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <br>
          <div class="progress">
               <div class="progress-bar bg-warning" role="progressbar" style="width: 75%" aria-valuenow="75"
                    aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <br>
          <div class="progress">
               <div class="progress-bar bg-danger" role="progressbar" style="width: 100%" aria-valuenow="100"
                    aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <br>
     </div>

     

   
</template>

<script>

     export default {
          components: {
               
          }
     }
</script>

<style scoped>

#boxes {
     padding: 1rem;
     margin: 1rem;
}
     h1,
     h3,
     p {
          font-family: 'Montserrat';
     }

     .title h1 {
          margin: 2rem;
          max-width: 90rem;
          text-align: center;
          padding: 1rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
     }

     .visit-list {

          margin: 1rem;
          max-width: 90rem;
          text-align: left;
          padding: 2rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);

     }


     .static {

          margin: 1rem;
          max-width: 60rem;
          text-align: left;
          padding: 2rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);

     }

     .table td {
          padding: 2rem;
     }


     .user-list {

          margin: 1rem;
          max-width: 90rem;
          text-align: left;
          padding: 2rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);

     }

     .divider {
          display: flex;

     }

     .list {
          display: flex;
          text-align: center;

     }

     .visit {
          background-color: aqua;
          margin: .5rem auto;
          max-width: 30rem;
          padding: 5rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
          height: 30vh;
     }

     nav {
          background-color: #1461ac;
     }


     .users {

          background-color: #066163;
          margin: .5rem auto;
          max-width: 30rem;
          text-align: left;
          padding: 5rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
          height: 30vh;
     }


     .total {
          background-color: #EBD671;
          margin: .5rem auto;
          max-width: 30rem;
          text-align: left;
          padding: 5rem;
          border-radius: 5px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
          height: 30vh;
     }


     nav {
          padding: 2rem;

     }



     li {
          padding: 20px;
          margin-left: 70px;
          font-family: 'Josefin Sans', sans-serif;

     }


     #dropdown {
          text-align: right;
     }



     ul,
     .link,
     .dropdown-item {
          font-weight: 500;
          color: #fff;
          list-style: none;
          text-decoration: none;
          font-family: 'Josefin Sans', sans-serif;
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