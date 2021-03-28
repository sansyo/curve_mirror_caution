# curve_mirror_caution

【要約】
【課題】
　簡単な構成により、反射物を利用した物体検出を行うことで、より安全な走行を支援する運転支援装置を提供する

【解決手段】
　自車両Mの前方を撮像するカメラを用いて、注視すべき反射物検出部分と、反射物画像内の注意物体検出部と、反射物画像内の注意物体移動方向判定部を備え、カメラ及び自車両Mの運転席からの死角になっている物体の存在と移動方向を検出する運転支援装置・報知システムを構成する。



※上記は、単一のカメラで撮像する例を示したが、異なる視点で撮像するカメラを用いても良い。



【特許請求の範囲】
【請求項１】
　自車両の前方を撮像するカメラと、
　自車両前方のカメラが撮像した画像から反射鏡（例：カーブミラー）領域を検出する検出器と、
　前記領域において注意物体が存在するか検出する検出部と、
　前記領域において検出された物体が動く方向を判定する判定部と、
　前記判定結果に基づき注意物体の存在および接近を乗員に報知する手段と、を備えたことを特徴とする運転支援装置。

【請求項２】
　前記判定結果に基づいて、自車両の走行制御を行う車両制御手段を備えたことを特徴とする請求項１に記載の運転支援装置

【請求項３】
　前記判定結果に基づいて、自車両の乗員に対し、注意物体の接近を報知する手段を備えたことを特徴とする請求項１に記載の運転支援装置。


【発明の詳細な説明】
【技術分野】
【０００１】
　本発明は、撮像した画像を用いて自車両の走行を制御しドライバーに危険を報知する運転支援装置に関する。

【背景技術】
【０００２】
【０００３】
【先行技術文献】
【０００４】
【特許文献１】
　後で
【発明の概要】
【発明が解決しようとする課題】
【０００５】
　ところで、近年の運転支援制御は、いわゆる自動運転などを含む制御へと高度化する傾向にある。これに伴い、より熟練した運転手に倣った運転支援制御を行うには、カメラに直接的に映る物体の検出のみならず、道路上に配置された反射鏡に映り込んだ物体の情報も考慮した、最適な運転支援を行うことが望ましい。

【０００６】
　その一方で、反射鏡に映り込んだ物体のサイズは小さく、また歪んでいるため、物体までの距離、種類や移動速度を定量化するアルゴリズムは、非常に複雑化する虞がある。

【０００７】
　本発明は上記事情に鑑みてなされたもので、簡単な物体の有無の判定と移動方向の判定のみにより、反射鏡の画像情報を活用した運転支援装置を提供することを目的とする。

【０００８】
　自車両の前方を撮像するカメラと、
　自車両前方のカメラが撮像した画像から反射鏡（例：カーブミラー）領域を検出する検出器と、
　前記領域において注意物体が存在するか検出する検出部と、
　前記領域において検出された物体が動く方向を判定する判定部と、
　前記判定結果に基づき注意物体の存在および接近を乗員に報知する手段と、
　前記判定結果に基づいて、自車両の走行制御を行う車両制御手段と、
　前記判定結果に基づいて、自車両の乗員に対し、注意物体の接近を報知する手段を備えたことを特徴とする運転支援装置である。

【発明の効果】
【０００９】
本発明の運転支援装置によれば、簡単な構成により、道路上の反射鏡内に映り込んだ物体の情報を考慮し、運転手に対して適切な運転支援を行うことができる。








明細書の書き方参考
https://www.j-platpat.inpit.go.jp/c1800/PU/JP-2020-052784/EF6B3F7DA1D26677BD545CF7CFC8335C62C83145B99DECFC3A92D34B52F7299D/11/ja


某自動車S社の面接中にアイデアを披露してしまったが不採用になってしまったため、
まぁ公知にしておこうと思いここに書きました。
