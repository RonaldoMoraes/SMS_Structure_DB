# SMS_Structure_DB
Sistemas Distribuídos - MySQL - Estrutura do banco de dados da parte da API
API_ENTRY_DATA_JSON:


CLIENT:
{
	"id":1,
	"name":"University",
	"api_key":"md5huhuhu12987hd192gdhua8"
}

EVENT:
{
	"id":1,
	"id_client":1,
	"date_queue_entry":"2015-10-05 23:24:54",
	"datetime_start":"2015-10-05 23:24:54",
	"datetime_end":"2015-11-15 20:24:54",
	"just_now":0, //0 se for um evento recorrente, 1 se for um evento unico
	"period":5, //de 5 em 5 dias, no horario do datetime_start
	"text":"Aqui vai a mensagem que sera destinada para os contatos abaixo."
}

PHONE:
{
	"id_event":"1",
	"cel_number":"9145-8401"
}
