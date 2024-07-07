```html
<div id="votesDisplay">Votes for Gojo: Loading...</div>

<script>
    let gojoVotes = localStorage.getItem('GojoVotes');
    document.getElementById('votesDisplay').textContent = `Votes for Gojo: ${gojoVotes}`;
</script>
