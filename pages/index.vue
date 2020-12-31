<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title text-4xl">Hoe staat de pet nu dan?</h1>
      <div class="links">
        <table class="table-auto mx-auto">
          <thead>
            <tr>
              <th class="w-1/2 text-left">Persoontje</th>
              <th class="w-1/2 text-left">Status pet</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="text-left">Bas</td>
              <td class="text-left">Wij komen</td>
            </tr>
            <tr>
              <td class="text-left">Borek</td>
              <td class="text-left">Daardoor dus blij!</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
td,
th {
  @apply p-1;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}

.links {
  padding-top: 15px;
}
</style>
