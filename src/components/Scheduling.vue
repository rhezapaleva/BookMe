<script>
export default {
  mounted() {
    Calendly.initInlineWidget({
      url: 'https://calendly.com/dominicj-2022',
      parentElement: document.getElementById('calendar'),
    });
    console.log('Component is mounted and Calendly widget is initialized');
  },
}
</script>


<template>
    
      <h2>Schedule an Appointment</h2>

      <div id="calendar" style="min-width:320px;height:750px;"></div>
      <!-- <CalendlyVue url="dominicj-2022" @event="logEvent" @event-details="logEvent" @error="logEvent"></CalendlyVue> -->
    
  
  
  </template>
  

  <style scoped>
   /* style="min-width:320px;height:580px;" */
  .scheduling {
    padding: 20px;
  }
  
  .scheduling div {
    margin: 10px 0;
  }
  
  .scheduling button {
    background-color: #007BFF;
    color: white;
    border: none;
    padding: 5px 10px;
    cursor: pointer;
  }


  </style>
  