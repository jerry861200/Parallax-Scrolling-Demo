<template>
  <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-left">
            Title
          </th>
          <th class="text-left">
            Description
          </th>
          <th class="text-left">
            URL
          </th>
        </tr>
      </thead>
      <tbody>
        <tr
          v-for="repo in githubRepo"
          :key="repo.title"
        >
          <td>{{ repo.title }}</td>
          <td>{{ repo.description }}</td>
          <td><a :href="repo.url" target="_blank">{{ repo.url }}</a></td>
        </tr>
      </tbody>
    </template>
  </v-simple-table>
</template>

<script>
export default {
  data(){
    return {
      githubRepo:[
        {
          title:'Firetodo',
          description:'A todoList app that displays CRUD function with firebase database',
          url:'https://github.com/jerry861200/fireTodo',
        },
        {
          title:'Mind test questionare',
          description:'A mind test that collects 2400 feedbacks from Dcard.',
          url:'https://github.com/jerry861200/Questionnaire',
        },
        {
          title:'Wedding',
          description:'A story tells about the law benefit of being married',
          url:'https://github.com/jerry861200/wedding',
        },
        {
          title:'PorkerGame',
          description:'A todoList app that ',
          url:'https://github.com/jerry861200/porkerGame',
        },
        {
          title:'.',
          description:'just nothing',
          url:'xxx',
        },
        {
          title:'.',
          description:'just nothing',
          url:'xxx',
        },
        {
          title:'.',
          description:'just nothing',
          url:'xxx',
        },
      ]
    }
  }
}
</script>

<style>

</style>