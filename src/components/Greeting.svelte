<script lang="ts">
  const currentTime = new Date()
  const currentHour = currentTime.getHours()

  let greeting = ""

  if (currentHour < 12) {
    greeting = "Buenos Días"
  } else if (currentHour < 18) {
    greeting = "Buenos Tardes"
    
  } else {
    greeting = "Buenos noches"  
  }
</script>

<h3 class="text-3xl font-bold my-5">{greeting}</h3>