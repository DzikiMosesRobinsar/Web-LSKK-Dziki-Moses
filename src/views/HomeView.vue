<template>
  <div class="home">
    <Navbar />
    <Section1 />
    <Keren />
    <Section2 />
    <Section3 />
    <Employee />
    <Contact />

  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Section1 from '@/components/Section1.vue'
import Keren from '@/components/Keren.vue'
import Section2 from '@/components/Section2.vue'
import Section3 from '@/components/Section3.vue'
import Employee from '@/components/Employee.vue'
import Contact from '@/components/Contact.vue'


export default {
  name: 'HomeView',
  components: {
    Navbar,
    Section1,
    Keren,
    Section2,
    Section3,
    Employee,
    Contact,
  }
}
</script>
