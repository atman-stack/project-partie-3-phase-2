<template>
    <footer class="footer  bg-success">

        


                  
                 <div class="copyright container text-default">
                        &copy; {{year}} <span class="">DW WM</span> All Right Reserved 
                </div>




    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
