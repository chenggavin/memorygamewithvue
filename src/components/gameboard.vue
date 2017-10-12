<template>
	<div class="gameboard" >
		<h2> this is a game board</h2>
		
    <table class="table">
        <tbody>
            <tr>
                <th scope="row">1</th>
                <td>Mark</td>
                <td>Otto</td>
                <td><cardfront></cardfront></td>
            </tr>
        </tbody>
    </table>
    </div>
		</body>
	</div>
</template>

<script>
  
    import cardfront from './cardfront.vue';


	export default {
		name : 'gameboard',
        components : {
        cardfront
    }	
	};
</script>

<style>
	



</style>




