# Nirvana Type-SS
![Nirvana Type-SS](https://pbs.twimg.com/media/DxmYjFzV4AAOaga.jpg)

## Nirvana Type-SSとは・・・
 Symmetric staggerという形式を採用した分割型キーボードになります。  
 通常のキーボード（Row stagger)との違いは左手側のずれが逆になっています。  
 ハの字型に開くことで、左手側も肩が自然な感じに開き楽にタイピングできるようになっています。  
 ※当然のことですが、個人の主観に基づいていますので個人差や様々なご意見はあるかと思います。
  
## Spec
| 項目 | 詳細 |
| :-- | :-- |
| 形式 | Sprit / Symmetric Stagger |
| 対応スイッチ | MX互換スイッチ(ロープロファイル非対応) |
| キー数 | 48 (1U*44/1.75U or 1.5U *4) |
| 制御基板 | Pro micro(atmega32u4) |
| 制御ソフト | qmk_firmware |
| LED対応 | Under Glowのみ対応 |

### 開発経緯とか余談です
 自作キーボードを始めてから、国内流通しているキットをいくつか作ったのですが、  
 RowStagger/Ortholinear/column-stagger、ここまで作った時点で、  
 どれも一長一短あったことで配置の規格？というかその手のことを調べました。
 そこで自分が使いやすそうと感じたのがSymmetric staggerだったのですが、  
 国内に流通してるキットに存在しないっぽい、開発されている物も分割タイプは見当たらない…  
 ということで自分で開発するに至りました。  
  
※厳密には全段1/4ズレなのでEqual Symmetrical Staggerに類すると思います。