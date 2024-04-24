<!-- <template>
    <v-main>
      <v-table>
        <thead>
          <tr>
            <th class="text-left">ID</th>
            <th class="text-left">name</th>
            <th class="text-left">email</th>
            <th class="text-left">password</th>
            <th class="text-left">password confirmation</th>            
            <th class="text-left">Action</th>
            <th class="text-left">Action</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="item in items" :key="item.name">
            <td>{{ item.id }}</td>
            <td>{{ item.name }}</td>
            <td>{{ item.email }}</td>
            <td>{{ item.password }}</td>
            <td>{{ item.password confirmation}}</td>
            <td>
              <button class="btn btn-primary44">Update</button>
             </td>
             <td>
              <button class="btn btn-primary44">Delete</button>
             </td>
          </tr>
        </tbody>
      </v-table>
    </v-main>
  </template>
  
  <script>
  import axios from "axios";
  
  export default {
    data() {
      return {
        items: [],
      };
    },
  
    methods: {
      async getUsers() {
        const response = await axios.get("http://127.0.0.1:8000/api/register");
        this.items = response.data;
      },
    },
  
    created() {
      this.getUsers();
    },
  };
  </script>
   -->