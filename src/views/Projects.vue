<template>
  <div 
    v-for='(project, index) in projects' 
    :key='project.id' 
  >
    #{{ index + 1}} - {{ project.title }}
  </div>

</template>
