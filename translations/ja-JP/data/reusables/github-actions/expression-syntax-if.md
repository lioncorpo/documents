`if`条件の中で式を使う場合、式構文({% raw %}`${{ }}`{% endraw %})を省略できます。これは、式に演算子が含まれていない場合、{% data variables.product.prodname_dotcom %}が自動的に`if`条件を式として評価するためです。 式に演算子が含まれている場合、明示的に評価されるようマークするためにその式を{% raw %}`${{ }}`{% endraw %}で囲まなければなりません。