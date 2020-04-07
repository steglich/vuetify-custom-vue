<template>
  <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <template v-for="header in headers">
            <th class="text-left" :key="header.name">{{ header.name }}</th>
          </template>
        </tr>
      </thead>
      <tbody>
        <slot />
      </tbody>
    </template>
  </v-simple-table>
</template>

<script>
  export default {
    props: {
      headers: { type: Array }
    }
  }
</script>