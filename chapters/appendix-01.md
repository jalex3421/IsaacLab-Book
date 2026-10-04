## 付録 次に読む公式リソース

以下は本書の確認に使った公式資料を中心にまとめたものです。`v3.0.0-EA`付きのURLは本書の対象版、Isaac Simの`latest`は更新されるページです。実際の導入時は、ページ上の版も確認してください。

| 読む順番 | 資料 | 調べる内容 |
| --- | --- | --- |
| 1 | [Isaac Labの対応表](https://github.com/isaac-sim/IsaacLab#isaac-sim-version-dependency) | LabとSimの組み合わせ |
| 2 | [Isaac Labの導入](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/setup/installation/index.html) | uv、自動導入、追加機能 |
| 3 | [Isaac Simの要件](https://docs.isaacsim.omniverse.nvidia.com/latest/installation/requirements.html) | GPU、OS、ドライバー、互換性 |
| 4 | [Isaac Simのインストール案内](https://docs.isaacsim.omniverse.nvidia.com/latest/installation/index.html) | ワークステーション、Python、コンテナー |
| 5 | [空の場面を作る](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/tutorials/00_sim/create_empty.html) | AppLauncherとSimulationContext |
| 6 | [関節モデルを操作する](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/tutorials/01_assets/run_articulation.html) | 配置、指令、状態更新、リセット |
| 7 | [アセットの取り込み](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/how-to/import_new_asset.html) | URDFとMJCFからUSDへの変換 |
| 8 | [アセット設定の作成](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/how-to/write_articulation_cfg.html) | ロボットの初期状態と駆動設定 |
| 9 | [センサー](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/concepts/sensors/index.html) | 各センサーの仕様と制約 |
| 10 | [バックエンドとプリセット](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/concepts/backends_and_presets.html) | 物理、描画、表示の選択 |
| 11 | [タスクの設計方式](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/concepts/task_workflows.html) | Manager-basedとDirect |
| 12 | [How-to Guides](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/how-to/index.html) | 次に取り組む個別の例 |
| 13 | [Sim2Real](https://isaac-sim.github.io/IsaacLab/v3.0.0-EA/source/policy_deployment/index.html) | 方策の出力と実機への接続 |

PPOをもう少し詳しく知りたい場合は、NVIDIA資料とは別に、[PPOの原論文](https://arxiv.org/abs/1707.06347)も参照できます。最初から式をすべて理解する必要はありません。経験を集める処理と方策を更新する処理を分けて読んでみてください。

公式のソースも、本文と同じタグで開きます。

- [空の場面のPythonソース](https://github.com/isaac-sim/IsaacLab/blob/v3.0.0-EA/scripts/tutorials/00_sim/create_empty.py)

- [関節モデルのPythonソース](https://github.com/isaac-sim/IsaacLab/blob/v3.0.0-EA/scripts/tutorials/01_assets/run_articulation.py)

- [依存関係の定義](https://github.com/isaac-sim/IsaacLab/blob/v3.0.0-EA/pyproject.toml)

- [Isaac Lab Discussions](https://github.com/isaac-sim/IsaacLab/discussions)

- [NVIDIA Isaac Sim Forum](https://forums.developer.nvidia.com/c/omniverse/isaac-sim/69)

