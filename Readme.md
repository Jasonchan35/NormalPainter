# NormalPainter
![](https://user-images.githubusercontent.com/1488611/27468607-b3e9e4d0-5825-11e7-954d-fca1a7a50417.gif)

Unity 上でポリゴンモデルの法線編集を可能にするツールです。
Unity 5.6 系以上、Windows (64bit) & Mac で動作します。

## 使い方
- [NormalPainter.unitypackage](https://github.com/unity3d-jp/NormalPainter/releases/download/20170623/NormalPainter.unitypackage) をプロジェクトにインポート
- Window -> Normal Painter でツールウィンドウを開く
- MeshRenderer か SkinnedMeshRenderer を持つオブジェクトを選択するとツールウィンドウに "Add NormalPainter" が出てくるのでそれを押す


## 実装されている機能
- 頂点、法線、タンジェント等の可視化
- 法線のペイント、回転、スケーリング等 (上の動画参照)
- 法線のミラーリング (Misc -> Mirroring)
- 法線の転写 (Edit -> Projection)
  - 各頂点から法線方向にレイを飛ばし、指定オブジェクトに当たった位置の法線を拾ってきます

- import / export
  - 法線 <-> 頂点の相互変換
  - 法線をテクスチャとしてエクスポート
  - 法線マップを頂点の法線としてインポート
  - .obj ファイルとしてエクスポート


## License
[MIT](LICENSE.txt)
