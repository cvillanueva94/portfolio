<template>
    <nav className="flex sm:justify-end space-x-4 pt-6 pr-8">
        <a href="#" className="rounded-lg px-3 py-2 text-slate-500 font-medium hover:text-slate-50">About</a>
        <a href="#" className="rounded-lg px-3 py-2 text-slate-500 font-medium hover:text-slate-50">Experience</a>
        <a href="#" className="rounded-lg px-3 py-2 text-slate-500 font-medium hover:text-slate-50">Work</a>
        <a href="#" className="rounded-lg px-3 py-2 text-slate-500 font-medium hover:text-slate-50">Contact</a>
        <a href="#" className="rounded-lg px-3 py-2 text-slate-500 font-medium border-2 border-bg-slate-500 hover:text-slate-50 hover:border-bg-slate-50">Resume</a>
    </nav>
</template>
  
<script>
export default {
name: 'NavBar',
props: {
    msg: String
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
  