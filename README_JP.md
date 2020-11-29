# Cz流MOD作成tips

##スタジオ用MOD
###ファイル構成
####必要なファイルについて
	スタジオ用とキャラメイク用それぞれ必要なファイルが異なります
	
__________＿＿＿スタジオ用＿＿＿＿＿＿＿＿＿＿＿_______________

	.zipmod
	　　│
	　　├　manifest.xml						　			　　　　　　　	
	　　│
	　　└　abdata
	  	　│
	  　	 ├(abdata以下任意の場所に）.unity3d			　
	  	　│
	  	　└ studio
            │
	  	      └ info
	   		       │
			         └(info以下任意の場所にフォルダ"NAME"）	
			        	│					
				        ├ItemCategory_XX_YYY.csv		
	        			│					
	        			├ItemGroup_"NAME".csv			
	        			│				
	        			└ItemList_XX_YYY_ZZZ.csv		
__________＿＿＿__________＿＿＿＿＿＿＿＿＿＿＿_______________
	
　①　manifest.xml

	MODの内部的な名前を決めます
	他のMODと被らないようにしてください


　②　.unity3d
	
	アイテムのモデルデータを格納しています
	addata以下ならどこにおいてもかまいません
	（筆者は.csvファイルと同じところに置いています）

　③　info 各csv
	
	info以下で各csvを読み込みます
	
