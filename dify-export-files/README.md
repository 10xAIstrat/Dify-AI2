## 「特化AIデバッグ」の「パラメータ抽出」について
<img width="404" height="127" alt="Screenshot 2025-12-26 03 29 22m" src="https://github.com/user-attachments/assets/6592fcbd-9fa4-4d2c-a22e-c357a563fcc9" /><br>
右端の二重四角のアイコンをクリックすると，簡単にコピーできます．<br>
「説明」欄に貼り付けてください．

### `fixed_code`に対応する，「説明」欄に入力すべき内容
```
LLMの出力から、[FIXED_CODE] と [/FIXED_CODE] の間にある「修正後のコード全文」をそのまま抽出してください。改行は保持し、余計な説明文や ``` などは含めないでください。
```
### `summary`に対応する，「説明」欄に入力すべき内容
```
LLMの出力から、[SUMMARY] と [/SUMMARY] の間にある「修正内容の要約」を抽出してください。
```
### `assumptions`に対応する，「説明」欄に入力すべき内容
```
LLMの出力から、[ASSUMPTIONS] と [/ASSUMPTIONS] の間にある「前提条件・仮定」を抽出してください。NONE と書かれている場合は "NONE" を返してください。
```
### `next_if_fails`に対応する，「説明」欄に入力すべき内容
```
LLMの出力から、[NEXT_IF_FAILS] と [/NEXT_IF_FAILS] の間にある「まだ失敗する場合の次の確認事項」を抽出してください。
```
