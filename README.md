This module "Bin::TSV::Conv" provides scripts for specific functionalities that deals about the information of a directory. 

The included commands are as follows.

 csel

 csv2tsv

 join2

 mtranspose

 xlsx2tsv

 
 Copyright (c) 2021 Toshiyuki SHIMONO. All rights reserved.
 This program is free software; you can redistribute it and/or
 modify it under the same terms as Perl itself.

-- 

メモ: 
 Bin::TSV::Conv はTSV形式ファイルのデータの変換に関わる。
 まだ追加すべきコマンドがひとつあったような気がする。(2021-05-29T00:02+0900 自分向けメモ)
 このモジュールに既に加えた5個のコマンドに沿って、さらに追加すべきものがありそう。ただし無闇に数は増やさないように気をつけて、追加する者は厳選すること。
 csv2tsv でうまく変換出来なかったデータファイルがあった(新型コロナ関連)。使っているモジュールの仕様かバグの可能性もある。再現を確認するなどして改良したい。ただし、このcsv2tsv は他の人も似たような意味でコマンドを作っているので、そちらも調査して、良いものが見つかったら、こちらのモジュールに収めたcsv2tsvの名前を変換するくらいが良いかも知れない。ただし、非常に良いものができたら、csv2tsvの名前は保持し続けるものとする。
