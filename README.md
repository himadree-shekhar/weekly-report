
5/26: 
- 保守作業: (O/D-Matrix)歩行者NetworkのBackup修正 [中]
- 保守作業: (O/D-Matrix)使用中の歩行者Profile削除確認 [中]
- 保守作業: (O/D-Matrix)歩行者のBackup Test(#) [中]
- ヘルプシステム更新: (CHM-Export): ....
- ISO27001:2023（JIS）説明会


● ※ ↓ [X] └──
~~ This is Strikethrough text ~~

**This text is _extremely_ important**


- 修正:Used-Profiles[中]  / NetworkListEditor: 
- Make New Branch: OD-Matrix [Import-CSV] 
- CHM-Export機能: 
- レポート作成: オンライン健康セミナー（がん講座）※配信期間：6/25 18時まで
- レポート作成: ISO27001:2023（JIS）説明会
- Office 365_account_switching
+ N3 週報:1

# 週報: 6月9日～6月13日
_________________________________
9日:
    ● グループミーティング
    ● 修正:Used-Profiles[中]
_________________________________
10日:
    ● 修正:Clone MemoryLeak[OK]
    ● 修正:Used-Profiles[中]
_________________________________
11日:
_________________________________
12日:
_________________________________
13日:
_________________________________

____________________________________________
Details :
____________________________________________
Next Week :
____________________________________________


GOAL :
Stop Delete in Cases:
    1. Generator-Case: Normal :  -> if pg is PedestriansGeneratorNormalClass then -> Show Warning : Used
    2. Generator-Case: O/D Matrix : -> else if pg is PedestriansGeneratorMatrixODClass then -> Show Warning : Used

And Show Warning (Regardless Of Active or Not):
    IDS_PEDESTRIANSPROFILE_USED =       'Cannot delete profile: "%s" is being used.';

***Note: Profile List is Multi-Selection > Show Warning per profile.

ButtonPeDeleteClick
↓