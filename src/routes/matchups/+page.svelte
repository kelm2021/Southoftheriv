<script>
	import { MatchupsAndBrackets } from '$lib/components';

	export let data;
	const {queryWeek, matchupsData, bracketsData, playersData, leagueTeamManagersData} = data;
</script>

<style>
    #main {
        position: relative;
        z-index: 1;
    }
</style>

<div id="main">
    <MatchupsAndBrackets {queryWeek} {matchupsData} {bracketsData} {playersData} {leagueTeamManagersData} />
</div>
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR_L2uJOH9jXVvouDI587NFSo8d4V6oxCkWSZ-9UTAAjuuL6pQRQg4z40vEkApRBAuteCTD9vvlub5J/pubhtml?gid=1459315646&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
