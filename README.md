# gms9999_zhcn
zh-CN translation for GameMaker:Studio 1.4.9999

这个项目用于翻译 GameMaker: Studio 的最终版本 1.4.9999。

<<<<<<< HEAD
本项目使用 OmegaT 进行外部翻译，Sisulizer 导入翻译结果后生成最终文件。
=======
本项目需使用 [Resource Hacker](http://www.angusj.com/resourcehacker/) 导入 `.res` 文件进行。

## 详细

汉化内容分为两个部分，一个是字符串（String Table），一个是 RC 数据（RC Data）。

其中字符串内只要是单引号内的内容均可进行翻译。

RC 数据内需要注意，仅 **Caption =** 、**Hint =**、**Lines.Strings =** 后的内容需要翻译（注意单引号），以及将 **Font.Height = ** 数值从 `-11` 改为 `-12` 外，其余均保持原状，且前 6 个数据不需要进行翻译（即从 ``TAboutDialog`` 开始进行翻译并校对）。

## 相关文件介绍

|                文件                |                             描述                             |
| :--------------------------------: | :----------------------------------------------------------: |
|           Translated.res           |               需进行汉化的文件（仅修改此文件）               |
|       Reference/Original.res       |        原版语言资源文件（英语，作为参考，不进行改动）        |
| Reference/bilvdehu163-1.4.1763.res | 由 碧绿的湖163 翻译的语言资源文件，版本 1.4.1763（作为参考，不进行改动） |

## 翻译情况（超长）

（✔: 完成翻译并校对 / !: 完成翻译但未校对 / ✘: 未完成翻译）

|  字符串   | 翻译情况 |           RC 数据            |         翻译情况         |
| :-------: | :------: | :--------------------------: | :----------------------: |
| 4030:2052 |    !     |         TAboutDialog         |            !             |
| 4031:2052 |    !     |         TActionForm          |            !             |
| 4032:2052 |    !     |       TAddRSSFeedForm        |            !             |
| 4033:2052 |    !     |        TAndroidCommon        |            !             |
| 4034:2052 |    !     |       TAssetStoreForm        |            ✘             |
| 4035:2052 |    !     |       TAssetStoreLogin       |            ✘             |
| 4036:2052 |    !     |       TAudioGroupsForm       |            !             |
| 4037:2052 |    !     |       TBackgroundForm        |            !             |
| 4038:2052 |    !     |          TBetaForm           |            !             |
| 4039:2052 |    !     |      TButtonDialogForm       | （无字符串，不需要翻译） |
| 4040:2052 |    !     |         TChangeForm          |            !             |
| 4041:2052 |    !     |          TCodeForm           |            !             |
| 4042:2052 |    !     |          TCommitLog          |            !             |
| 4043:2052 |    !     |         TCompileForm         |            !             |
| 4044:2052 |    !     |       TCompletionForm        | （无字符串，不需要翻译） |
| 4045:2052 |    !     |        TConstantForm         |            ✘             |
| 4046:2052 |    ✘     |      TCustomKeyBindForm      |            !             |
| 4047:2052 |    ✘     |        TDataFileForm         |            ✘             |
| 4048:2052 |    ✘     |          TDataForm           |            ✘             |
| 4049:2052 |    ✘     |          TEventForm          |            ✘             |
| 4050:2052 |    ✘     |         TExportForm          |            ✘             |
| 4051:2052 |    ✘     | TExtensionConstantProperties |            ✘             |
| 4052:2052 |    ✘     |   TExtensionFileProperties   |            ✘             |
| 4053:2052 |    ✘     |        TExtensionForm        |            ✘             |
| 4054:2052 |    ✘     | TExtensionFunctionProperties |            ✘             |
| 4055:2052 |    ✘     |    TExtensionLibraryForm     |            ✘             |
| 4056:2052 |    ✘     |    TExtensionPackageHelp     |            ✘             |
| 4057:2052 |    ✘     | TExtensionPackageProperties  |            ✘             |
| 4058:2052 |    ✘     |       TExtInstallForm        |            ✘             |
| 4059:2052 |    ✘     |          TFontForm           |            ✘             |
| 4060:2052 |    ✘     |          TFontRange          |            ✘             |
| 4061:2052 |    ✘     |          TGridForm           |            ✘             |
| 4062:2052 |    ✘     |          THelpForm           |            ✘             |
| 4063:2052 |    ✘     |       THelpOptionsForm       |            ✘             |
| 4064:2052 |    ✘     |       TImageEditorForm       |            ✘             |
| 4065:2052 |    ✘     |         TImagesForm          |            ✘             |
| 4066:2052 |    ✘     |         TImportForm          |            ✘             |
| 4067:2052 |    ✘     |   TImportOldVersionWarning   |            ✘             |
| 4068:2052 |    ✘     |        TInstanceOrder        |            ✘             |
| 4069:2052 |    ✘     |   TInstancePropertiesForm    |            ✘             |
| 4070:2052 |    ✘     |          TKeyBinds           |            ✘             |
| 4071:2052 |    ✘     |      TLicenseTargetForm      |            ✘             |
| 4072:2052 |    ✘     |          TMainForm           |            ✘             |
| 4073:2052 |    ✘     |      TMakerAccount2Step      |            ✘             |
| 4074:2052 |    ✘     |     TMaker_ConfigCreate      |            ✘             |
| 4075:2052 |    ✘     |     TMaker_ConfigManager     |            ✘             |
| 4076:2052 |    ✘     |          TMaskForm           |            ✘             |
| 4077:2052 |    ✘     |       TNewProjectForm        |            ✘             |
| 4078:2052 |    ✘     |          TNewsForm           |            ✘             |
| 4079:2052 |    ✘     |         TObjectForm          |            ✘             |
| 4080:2052 |    ✘     |    TObjectInformationForm    |            ✘             |
| 4081:2052 |    ✘     |     TObjectPhysicsShape      |            ✘             |
| 4082:2052 |    ✘     |         TOptionForm          |            ✘             |
| 4083:2052 |    ✘     |      TOptionStudioForm       |            ✘             |
| 4084:2052 |    ✘     |         TPasswordDlg         |            ✘             |
| 4085:2052 |    ✘     |          TPathForm           |            ✘             |
| 4086:2052 |    ✘     |        TPlacementForm        |            ✘             |
| 4087:2052 |    ✘     |       TPlayerBuildForm       |            ✘             |
| 4088:2052 |    ✘     |       TPreferencesForm       |            ✘             |
| 4089:2052 |    ✘     |        TProgressForm         |            ✘             |
| 4090:2052 |    ✘     |        TResizeDialog         |            ✘             |
| 4091:2052 |    ✘     |      TResourceIconForm       |            ✘             |
| 4092:2052 |    ✘     |      TRoomControlsForm       |            ✘             |
| 4093:2052 |    ✘     |          TRoomForm           |            ✘             |
| 4094:2052 |    ✘     |      TRSSFeedProperties      |            ✘             |
| 4095:2052 |    ✘     |         TSaveAsForm          |            ✘             |
| 4096:2052 |    ✘     |       TSCM_ConfigForm        |            ✘             |
|           |          |      TSCM_ConflictForm       |            ✘             |
|           |          |         TSCM_History         |            ✘             |
|           |          |       TSCM_StatusForm        |            ✘             |
|           |          |         TScriptForm          |            ✘             |
|           |          |       TScriptInfoForm        |            ✘             |
|           |          |         TShaderForm          |            ✘             |
|           |          |          TSoundForm          |            ✘             |
|           |          |        TSourceControl        |            ✘             |
|           |          |     TSpineAgreementForm      |            ✘             |
|           |          |      TSpriteEditorForm       |            ✘             |
|           |          |         TSpriteForm          |            ✘             |
|           |          |       TStandAloneForm        |            ✘             |
|           |          | TSteamWorkShopAgreementForm  |            ✘             |
|           |          |      TSteamWorkShopForm      |            ✘             |
|           |          |     TStorePropertiesForm     |            ✘             |
|           |          |          TStripForm          |            ✘             |
|           |          |      TStudioPreferences      |            ✘             |
|           |          |        TSupportSearch        |            ✘             |
|           |          |        TTimeLineForm         |            ✘             |
|           |          |   TTimeLineInformationForm   |            ✘             |
|           |          |         TTranspForm          |            ✘             |
|           |          |         TTriggerForm         |            ✘             |
|           |          |        TValuesDialog         |            ✘             |
>>>>>>> a438ce4d533370835d0ad435e3e130fada93d377
