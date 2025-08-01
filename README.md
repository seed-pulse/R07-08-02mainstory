# R07-08-02mainstory
4:46
Last login: Thu Jul 31 06:47:46 on ttys000
masuyamakazuki@masuyamaMacBook-Pro ~ % nano azure_gpt_api_chatbot.py

masuyamakazuki@masuyamaMacBook-Pro ~ % python azure_gpt_api_chatbot.py

zsh: command not found: python
masuyamakazuki@masuyamaMacBook-Pro ~ % python3 azure_gpt_api_chatbot.py

【ローカルAGI × Azure OpenAI APIボット】
終了するには 'exit' を入力してください。
あなた: こんにちは
GPT: こんにちは！😊 今日はどんなお手伝いをしましょうか？
あなた: ローカルのPCでチャットしています。        
GPT: なるほど、チャットを楽しんでいるんですね！✨ 他にも話したいことや質問があれば、何でも気軽に聞いてくださいね！
あなた: ^CTraceback (most recent call last):
  File "/Users/masuyamakazuki/azure_gpt_api_chatbot.py", line 34, in <module>
    user = input("あなた: ")
           ^^^^^^^^^^^^^^^^^
KeyboardInterrupt

masuyamakazuki@masuyamaMacBook-Pro ~ % nano intent_controller.py

masuyamakazuki@masuyamaMacBook-Pro ~ % python intent_controller.py

zsh: command not found: python
masuyamakazuki@masuyamaMacBook-Pro ~ % python intent_controller.py

masuyamakazuki@masuyamaMacBook-Pro ~ % python3 intent_controller.py

【ローカルAGI×API統合コントローラ】'exit'で終了, '/status'で自己説明
あなた: こんにちは
API: ('【API返答】こんにちは', 'api')
あなた: 動きました
API: ('【API返答】動きました', 'api')
あなた: /status
■現在の状態: {'知識数': 2, '会話履歴数': 5}
あなた: exit
終了します。
masuyamakazuki@masuyamaMacBook-Pro ~ % 

【ローカルAGI×API統合コントローラ】'exit'で終了, '/status'で自己説明
あなた: こんにちは
API: ('【API返答】こんにちは', 'api')
あなた: 動きました
API: ('【API返答】動きました', 'api')
あなた: /status
■現在の状態: {'知識数': 2, '会話履歴数': 5}
あなた: exit
終了します。
masuyamakazuki@masuyamaMacBook-Pro ~ % 
----
インテントコントローラー作成完了
自己分析のためのUI
----


