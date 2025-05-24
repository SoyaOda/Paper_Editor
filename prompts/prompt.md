対象となる github URL：https://github.com/SoyaOda/Paper_Editor

[drafts の内容]
・original_draft.txt：編集前の原稿
・editing_draft_until_results.txt：Reviews に対応するように編集した原稿(Results まで)

[reviews の内容]
・Epsilon-Reviews-Results まで.txt：original_draft に対する Reviewer Epsilon の Review リスト（対象が Results まで）
・Gamma-Reviews-Results まで.txt：original_draft に対する Reviewer Gamma の Review リスト（対象が Results まで）

[現状]
・original_draft に対して Results までの内容を Reviews に沿って編集している。現段階で editing_draft_until_results を作成している。

[editing_draft_until_results のルール]
・修正には追記と削除の二つがある。
・original_draft と比較し、{追記内容}を$$Gamma-1, Comment$${追記内容}$/Gamma-1$/のように囲いわかるようにしている。その際、Gamma-1 は Review の Gamma-1 に対応する修正ということである。（Epsilon-2-2 は Epsilon-2 の Review の中に修正を促す内容が複数あり、その中の 2 つ目ということである。）また、Comment は、対応する修正内容（主に追記内容）に対する上司のコメントである。
・original_draft と比較し、同様に、{削除内容}を%%Gamma-1%%{削除内容}%/Gamma-1%/のように囲いわかるようにしている。

[reviews のルール]
・各 review に対して、どこを対象とした review かを対象箇所で述べ、修正方針を【修正方針】で述べている。

[命令]
現状の Results までの内容に対して、きちんと reviews と editing_draft_until_results が対応しているか詳細に確認して。
