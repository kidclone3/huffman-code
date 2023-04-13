<div class="w-60 relative mt-6">
<div class="relative w-40 h-40">
  <v-click>
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="imgs/pic1.png"
    />
</v-click>
  <v-click>
    <img
      v-motion
      :initial="{ y: 300, x: 500, scale: 2 }"
      :enter="final"
      class="absolute left-0 right-0 bottom-0"
      src="imgs/pic2.png"
    />
    </v-click>
    <v-click>
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="imgs/pic3.png"
    />
    </v-click>
    <v-click>
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="imgs/pic4.png"
    />
    </v-click>
  </div>
</div>