<script lang="ts">
    const currentTime = new Date()
    const currentHour = currentTime.getHours()

    let greeting = ""

    if(currentHour < 12){
        greeting = "Good Morning"
    }else if (currentHour <18){
        greeting = "Good afternoon"
    }else{
        greeting = "Good evening"
    }
</script>

<h1 class="text-4xl pt-5 font-bold">{greeting}</h1>