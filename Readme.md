# jupyter notebookについて

企業で使うにはどれがいいのか？  

1. jupyter notebook(classic)
2. jupyter lab
3. jupyter hub
1. other docker container (LC4RI、operation hub)  
https://literate-computing.github.io/  

考えるべき事項  
1.複数人で利用する→ jupyter hub  
2.いつ実行したかわかる→ execute_time (1-4可能)  
　classic notebookならnbextension, jupyterlabにもあり  
　https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/execute_time/readme.html  
3.read onlyにもできるようにしたい  
　freeze可能（1,4）  
4.CLIでもやりたい  
5.スケジュール実行したい  
→いずれもpapermillで実行可能  
6.同じセルを実行しても過去の結果が残るようにしたい  
→4 にてmulti_output  

