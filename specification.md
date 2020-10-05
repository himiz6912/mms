# 業務アプリケーション仕様書

## システム構成

| 名称 | 種類 | 概要 | 備考 |
|---|---|---|---|---|
| 保守管理システム | Desktop App | 保守点検の見積、契約管理、点検管理 | - |
| 行動管理システム | Desktop App | スタッフの行動管理、タスクの管理 | - |
| タスク管理 | Mobile App | スタッフが所持する会社携帯用のアプリ | - |

## アプリ詳細

### 保守管理システム

#### ユースケース

| 名称 | 概要 | 利用者 |
|---|---|---|
| 見積作成管理 | タブレット、PCで保守契約の見積を作成する。 | 営業担当 |
| 契約システム連携 | 登録された見積と契約システムの契約情を紐づける。 | 点検管理者 |
| 運用情報管理 | 緊急連絡先や対応履歴等の物件情報を管理する。 | 点検管理者、点検者 |
| 点検実施管理 | 点検アポ、発注、結果管理、集計 | 点検者 |

#### Entity

OMS_Dummy_Contract_Data_1 (MMS_SIMS_Dummy_Data_1)
OMS_Dummy_Contract_Data_2 (MMS_SIMS_Dummy_Data_2)

MMS_SIMS_dummy_data_1 --> OMS_dummy_contract_data_1
MMS_SIMS_dummy_data_2 --> OMS_dummy_contract_data_2
MMS_estimate_site --> OMS_estimate_site
MMS_maintenance_model --> OMS_maintenance_model
MMS_estimate_contractor --> OMS_estimate_contractor
MMS_Maintenance_Info --> OMS_maintenance_info
MMS_contract_equipment --> OMS_contract_equipment
MMS_contract_info --> OMS_contract_info



### 行動管理システム


### タスク管理アプリ
