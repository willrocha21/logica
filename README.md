# Execício de Lógica - DIO
<?php
/**
 * 
 */
class Rotina{
	
	function executa($texto){
		echo '<p>'.$texto.'</p>';		
	}
}


$r = new Rotina;

$r->executa('- Acordar as 6hs.');
$r->executa('- Tomar café.');
$r->executa('- Molhar a grama.');
$r->executa('- Dar comida pro cachorro.');
$r->executa('- Escovar os dentes.');
$r->executa('- Ir para o trabalho.');
$r->executa('- Voltar para casa.');
$r->executa('- Estudar e trabalhar mais um pouco.');
$r->executa('- Tomar banho.');
$r->executa('- Dormir sabe lá Deus que horas.');
