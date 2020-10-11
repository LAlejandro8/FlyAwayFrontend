<template>
  <div class="container-fluid mt-4">
    <h1 class="h1">Destinos</h1>
    <p>Eliga su destino</p>
    <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        { vuelo: 'FL001', clase: 'A1', origen: 'Cali', destino: 'Bogota', fecha_vuelo: '10/05/2020 18:00', valor: 150000 },
        { vuelo: 'FL101', clase: 'B2', origen: 'Medellin', destino: 'Bogota', fecha_vuelo: '10/05/2020 18:00', valor: 780000 },
        { vuelo: 'FL021', clase: 'C3', origen: 'Cartagena', destino: 'Huila', fecha_vuelo: '10/05/2020 18:00', valor: 1554000 },
        { vuelo: 'FL023', clase: 'D4', origen: 'Choco', destino: 'Cali', fecha_vuelo: '10/05/2020 18:00', valor: 7880000 }
      ]
    }
  }
}
</script>
