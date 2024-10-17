<!-- Швидка вставка відкриваючого #region та закриваючого #endregion для більш зручної структурізації коду -->
<!-- Для вставки регіонів html та css прописуємо "regh" та "regs" відповідно, та тиснемно Enter-->
<!-- Знизу зліва у VSCode відкриваємо налаштування, переходимо в пункт Snippets,
тиснемо на "New global snippets file..." та вставляємо код з цього файлу -->

{
	"HTML Region": {
		"prefix": "regh",
		"body": [
			"<!-- #region ${1:regionname} -->",
			"$0",
			"<!-- #endregion -->"
		],
		"description": "HTML region"
	},
	"CSS Region": {
		"prefix": "regs",
		"body": [
			"/* #region ${1:regionname} */",
			"$0",
			"/* #endregion */"
		],
		"description": "CSS region"
	}
}