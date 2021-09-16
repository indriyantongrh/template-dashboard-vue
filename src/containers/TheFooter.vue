<template>
  <CFooter :fixed="false">
    <!-- <div>

      <span class="ml-1">&copy; {{new Date().getFullYear()}} PT. Bank Negara Indonesia.</span>
    </div> -->
    <div class="mfs-auto">
    <span class="ml-1">&copy; {{new Date().getFullYear()}} PT. Bank Negara Indonesia .Tbk </span>
    </div>
  </CFooter>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>
