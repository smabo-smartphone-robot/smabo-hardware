# smabo-hardware  <!-- omit in toc --> 

本リポジトリでは
- smaboの各3Dモデル（stl, step）
- 各パーツの組み立て手順

を管理しています。

> [!NOTE]
> それぞれのパーツの組み立て手順は[smaboサイト](https://smabo-smartphone-robot.github.io)を参考にしてください。

# 目次 <!-- omit in toc --> 

- [ファイル一覧](#ファイル一覧)
  - [arm](#arm)
    - [sg90](#sg90)
      - [sg90\_0\_base\_plate.stl](#sg90_0_base_platestl)
      - [sg90\_1\_concave.stl](#sg90_1_concavestl)
      - [sg90\_1\_convex.stl](#sg90_1_convexstl)
      - [sg90\_2.stl](#sg90_2stl)
      - [sg90\_3\_concave.stl](#sg90_3_concavestl)
      - [sg90\_3\_convex.stl](#sg90_3_convexstl)
      - [sg90\_4\_concave.stl](#sg90_4_concavestl)
      - [sg90\_4\_convex.stl](#sg90_4_convexstl)
      - [sg90\_5\_concave.stl](#sg90_5_concavestl)
      - [sg90\_5\_convex.stl](#sg90_5_convexstl)
      - [sg90\_5\_hand.stl](#sg90_5_handstl)
  - [base](#base)
      - [base.stl](#basestl)
      - [bread\_board\_stopper.stl](#bread_board_stopperstl)
      - [bread\_board\_stopper\_bottom\_l.stl](#bread_board_stopper_bottom_lstl)
      - [bread\_board\_stopper\_bottom\_r.stl](#bread_board_stopper_bottom_rstl)
      - [cover\_back\_bread\_board.stl](#cover_back_bread_boardstl)
      - [in\_base\_plate\_template.stl](#in_base_plate_templatestl)
      - [in\_base\_plate\_wire\_hole.stl](#in_base_plate_wire_holestl)
      - [mini\_bread\_boad\_stand.stl](#mini_bread_boad_standstl)
      - [mini\_bread\_board\_stand.stl](#mini_bread_board_standstl)
      - [padding\_plate.stl](#padding_platestl)
      - [pca9685\_stopper\_l.stl](#pca9685_stopper_lstl)
      - [pca9685\_stopper\_r.stl](#pca9685_stopper_rstl)
      - [pca9685\_stopper\_top.stl](#pca9685_stopper_topstl)
  - [battery\_box](#battery_box)
      - [mobile\_battery\_case\_partition.stl](#mobile_battery_case_partitionstl)
      - [mobile\_battery\_cover\_length\_plus\_15mm.stl](#mobile_battery_cover_length_plus_15mmstl)
      - [mobile\_battery\_cover\_length\_plus\_7.5mm.stl](#mobile_battery_cover_length_plus_75mmstl)
      - [mobile\_battery\_cover\_template.stl](#mobile_battery_cover_templatestl)
  - [camera](#camera)
    - [raspi\_camera](#raspi_camera)
      - [raspi\_camera\_stand\_bottom.stl](#raspi_camera_stand_bottomstl)
      - [raspi\_camera\_stand\_front.stl](#raspi_camera_stand_frontstl)
  - [hand](#hand)
    - [sg90](#sg90-1)
      - [arm\_hand.stl](#arm_handstl)
      - [sg90\_base.stl](#sg90_basestl)
      - [sg90\_plate\_1.stl](#sg90_plate_1stl)
      - [sg90\_plate\_2.stl](#sg90_plate_2stl)
  - [lidar](#lidar)
    - [a1m8](#a1m8)
      - [rp\_lidar\_a1\_stand.stl](#rp_lidar_a1_standstl)
  - [magsafe](#magsafe)
      - [cover\_magsage.stl](#cover_magsagestl)
  - [mobile\_robot](#mobile_robot)
    - [DG01D-E](#dg01d-e)
      - [DG01D-E\_stopper1\_L.stl](#dg01d-e_stopper1_lstl)
      - [DG01D-E\_stopper1\_R.stl](#dg01d-e_stopper1_rstl)
      - [DG01D-E\_stopper2\_L.stl](#dg01d-e_stopper2_lstl)
      - [DG01D-E\_stopper2\_R.stl](#dg01d-e_stopper2_rstl)
      - [DG1D-E\_bottom.stl](#dg1d-e_bottomstl)
    - [dc\_motor\_caster](#dc_motor_caster)
      - [dc\_motor\_caster.stl](#dc_motor_casterstl)
    - [tt\_motor](#tt_motor)
      - [tt\_motor\_bottom.stl](#tt_motor_bottomstl)
      - [tt\_motor\_stopper1.stl](#tt_motor_stopper1stl)
      - [tt\_motor\_stopper2.stl](#tt_motor_stopper2stl)
  - [pan](#pan)
    - [mg996r](#mg996r)
      - [pan\_adapter.stl](#pan_adapterstl)
      - [pan\_plate\_top.stl](#pan_plate_topstl)
      - [pan\_stand\_left.stl](#pan_stand_leftstl)
      - [pan\_stand\_right.stl](#pan_stand_rightstl)
  - [raspi](#raspi)
      - [poll\_25mm.stl](#poll_25mmstl)
      - [raspi\_stand.stl](#raspi_standstl)
      - [raspi\_stopper1.stl](#raspi_stopper1stl)
      - [raspi\_stopper2.stl](#raspi_stopper2stl)
      - [raspi\_top\_plate.stl](#raspi_top_platestl)
  - [smart\_phone](#smart_phone)
      - [cover\_smartphone\_base.stl](#cover_smartphone_basestl)
      - [smartphone\_long\_width\_75\_height\_11.stl](#smartphone_long_width_75_height_11stl)
      - [smartphone\_short\_width\_37\_height\_11.stl](#smartphone_short_width_37_height_11stl)
  - [template](#template)
      - [cover\_back\_depth\_5\_template.stl](#cover_back_depth_5_templatestl)
      - [cover\_back\_template.stl](#cover_back_templatestl)
      - [cover\_template.stl](#cover_templatestl)


# ファイル一覧

各パーツにおけるファイルの一覧を記載します。

## arm

ロボットアームのコンポーネント集です。

### sg90

SG90サーボモーターを使用したアームのパーツです。

#### sg90_0_base_plate.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_0_base_plate.stl)

![sg90_0_base_plate](images/stl/arm/sg90/sg90_0_base_plate.jpg)

#### sg90_1_concave.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_1_concave.stl)

![sg90_1_concave](images/stl/arm/sg90/sg90_1_concave.jpg)

#### sg90_1_convex.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_1_convex.stl)

![sg90_1_convex](images/stl/arm/sg90/sg90_1_convex.jpg)

#### sg90_2.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_2.stl)

![sg90_2](images/stl/arm/sg90/sg90_2.jpg)

#### sg90_3_concave.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_3_concave.stl)

![sg90_3_concave](images/stl/arm/sg90/sg90_3_concave.jpg)

#### sg90_3_convex.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_3_convex.stl)

![sg90_3_convex](images/stl/arm/sg90/sg90_3_convex.jpg)

#### sg90_4_concave.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_4_concave.stl)

![sg90_4_concave](images/stl/arm/sg90/sg90_4_concave.jpg)

#### sg90_4_convex.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_4_convex.stl)

![sg90_4_convex](images/stl/arm/sg90/sg90_4_convex.jpg)

#### sg90_5_concave.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_5_concave.stl)

![sg90_5_concave](images/stl/arm/sg90/sg90_5_concave.jpg)

#### sg90_5_convex.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_5_convex.stl)

![sg90_5_convex](images/stl/arm/sg90/sg90_5_convex.jpg)

#### sg90_5_hand.stl

[📱 3Dビューアーで開く](stl/arm/sg90/sg90_5_hand.stl)

![sg90_5_hand](images/stl/arm/sg90/sg90_5_hand.jpg)

## base

ロボットの基板です。

#### base.stl

[📱 3Dビューアーで開く](stl/base/base.stl)

![base](images/stl/base/base.jpg)

#### bread_board_stopper.stl

[📱 3Dビューアーで開く](stl/base/bread_board_stopper.stl)

![bread_board_stopper](images/stl/base/bread_board_stopper.jpg)

#### bread_board_stopper_bottom_l.stl

[📱 3Dビューアーで開く](stl/base/bread_board_stopper_bottom_l.stl)

![bread_board_stopper_bottom_l](images/stl/base/bread_board_stopper_bottom_l.jpg)

#### bread_board_stopper_bottom_r.stl

[📱 3Dビューアーで開く](stl/base/bread_board_stopper_bottom_r.stl)

![bread_board_stopper_bottom_r](images/stl/base/bread_board_stopper_bottom_r.jpg)

#### cover_back_bread_board.stl

[📱 3Dビューアーで開く](stl/base/cover_back_bread_board.stl)

![cover_back_bread_board](images/stl/base/cover_back_bread_board.jpg)

#### in_base_plate_template.stl

[📱 3Dビューアーで開く](stl/base/in_base_plate_template.stl)

![in_base_plate_template](images/stl/base/in_base_plate_template.jpg)

#### in_base_plate_wire_hole.stl

[📱 3Dビューアーで開く](stl/base/in_base_plate_wire_hole.stl)

![in_base_plate_wire_hole](images/stl/base/in_base_plate_wire_hole.jpg)

#### mini_bread_boad_stand.stl

[📱 3Dビューアーで開く](stl/base/mini_bread_boad_stand.stl)

![mini_bread_boad_stand](images/stl/base/mini_bread_boad_stand.jpg)

#### mini_bread_board_stand.stl

[📱 3Dビューアーで開く](stl/base/mini_bread_board_stand.stl)

![mini_bread_board_stand](images/stl/base/mini_bread_board_stand.jpg)

#### padding_plate.stl

[📱 3Dビューアーで開く](stl/base/padding_plate.stl)

![padding_plate](images/stl/base/padding_plate.jpg)

#### pca9685_stopper_l.stl

[📱 3Dビューアーで開く](stl/base/pca9685_stopper_l.stl)

![pca9685_stopper_l](images/stl/base/pca9685_stopper_l.jpg)

#### pca9685_stopper_r.stl

[📱 3Dビューアーで開く](stl/base/pca9685_stopper_r.stl)

![pca9685_stopper_r](images/stl/base/pca9685_stopper_r.jpg)

#### pca9685_stopper_top.stl

[📱 3Dビューアーで開く](stl/base/pca9685_stopper_top.stl)

![pca9685_stopper_top](images/stl/base/pca9685_stopper_top.jpg)

## battery_box

バッテリーボックスのコンポーネント集です。

#### mobile_battery_case_partition.stl

[📱 3Dビューアーで開く](stl/battery_box/mobile_battery_case_partition.stl)

![mobile_battery_case_partition](images/stl/battery_box/mobile_battery_case_partition.jpg)

#### mobile_battery_cover_length_plus_15mm.stl

[📱 3Dビューアーで開く](stl/battery_box/mobile_battery_cover_length_plus_15mm.stl)

![mobile_battery_cover_length_plus_15mm](images/stl/battery_box/mobile_battery_cover_length_plus_15mm.jpg)

#### mobile_battery_cover_length_plus_7.5mm.stl

[📱 3Dビューアーで開く](stl/battery_box/mobile_battery_cover_length_plus_7.5mm.stl)

![mobile_battery_cover_length_plus_7.5mm](images/stl/battery_box/mobile_battery_cover_length_plus_7.5mm.jpg)

#### mobile_battery_cover_template.stl

[📱 3Dビューアーで開く](stl/battery_box/mobile_battery_cover_template.stl)

![mobile_battery_cover_template](images/stl/battery_box/mobile_battery_cover_template.jpg)

## camera

カメラモジュールのコンポーネント集です。

### raspi_camera

Raspberry Piカメラモジュール用のパーツです。

#### raspi_camera_stand_bottom.stl

[📱 3Dビューアーで開く](stl/camera/raspi_camera/raspi_camera_stand_bottom.stl)

![raspi_camera_stand_bottom](images/stl/camera/raspi_camera/raspi_camera_stand_bottom.jpg)

#### raspi_camera_stand_front.stl

[📱 3Dビューアーで開く](stl/camera/raspi_camera/raspi_camera_stand_front.stl)

![raspi_camera_stand_front](images/stl/camera/raspi_camera/raspi_camera_stand_front.jpg)

## hand

ロボットハンドのコンポーネント集です。

### sg90

SG90サーボモーターを使用したハンドのパーツです。

#### arm_hand.stl

[📱 3Dビューアーで開く](stl/hand/sg90/arm_hand.stl)

![arm_hand](images/stl/hand/sg90/arm_hand.jpg)

#### sg90_base.stl

[📱 3Dビューアーで開く](stl/hand/sg90/sg90_base.stl)

![sg90_base](images/stl/hand/sg90/sg90_base.jpg)

#### sg90_plate_1.stl

[📱 3Dビューアーで開く](stl/hand/sg90/sg90_plate_1.stl)

![sg90_plate_1](images/stl/hand/sg90/sg90_plate_1.jpg)

#### sg90_plate_2.stl

[📱 3Dビューアーで開く](stl/hand/sg90/sg90_plate_2.stl)

![sg90_plate_2](images/stl/hand/sg90/sg90_plate_2.jpg)

## lidar

LiDARセンサーのコンポーネント集です。

### a1m8

RP LiDAR A1M8用のパーツです。

#### rp_lidar_a1_stand.stl

[📱 3Dビューアーで開く](stl/lidar/a1m8/rp_lidar_a1_stand.stl)

![rp_lidar_a1_stand](images/stl/lidar/a1m8/rp_lidar_a1_stand.jpg)

## magsafe

MagSafe互換マウントのコンポーネント集です。

#### cover_magsage.stl

[📱 3Dビューアーで開く](stl/magsafe/cover_magsage.stl)

![cover_magsage](images/stl/magsafe/cover_magsage.jpg)

## mobile_robot

移動ロボットのコンポーネント集です。

### DG01D-E

DG01D-Eギアモーター用のパーツです。

#### DG01D-E_stopper1_L.stl

[📱 3Dビューアーで開く](stl/mobile_robot/DG01D-E/DG01D-E_stopper1_L.stl)

![DG01D-E_stopper1_L](images/stl/mobile_robot/DG01D-E/DG01D-E_stopper1_L.jpg)

#### DG01D-E_stopper1_R.stl

[📱 3Dビューアーで開く](stl/mobile_robot/DG01D-E/DG01D-E_stopper1_R.stl)

![DG01D-E_stopper1_R](images/stl/mobile_robot/DG01D-E/DG01D-E_stopper1_R.jpg)

#### DG01D-E_stopper2_L.stl

[📱 3Dビューアーで開く](stl/mobile_robot/DG01D-E/DG01D-E_stopper2_L.stl)

![DG01D-E_stopper2_L](images/stl/mobile_robot/DG01D-E/DG01D-E_stopper2_L.jpg)

#### DG01D-E_stopper2_R.stl

[📱 3Dビューアーで開く](stl/mobile_robot/DG01D-E/DG01D-E_stopper2_R.stl)

![DG01D-E_stopper2_R](images/stl/mobile_robot/DG01D-E/DG01D-E_stopper2_R.jpg)

#### DG1D-E_bottom.stl

[📱 3Dビューアーで開く](stl/mobile_robot/DG01D-E/DG1D-E_bottom.stl)

![DG1D-E_bottom](images/stl/mobile_robot/DG01D-E/DG1D-E_bottom.jpg)

### dc_motor_caster

直流モーター用キャスターです。

#### dc_motor_caster.stl

[📱 3Dビューアーで開く](stl/mobile_robot/dc_motor_caster.stl)

![dc_motor_caster](images/stl/mobile_robot/dc_motor_caster.jpg)

### tt_motor

TTモーター用のパーツです。

#### tt_motor_bottom.stl

[📱 3Dビューアーで開く](stl/mobile_robot/tt_motor/tt_motor_bottom.stl)

![tt_motor_bottom](images/stl/mobile_robot/tt_motor/tt_motor_bottom.jpg)

#### tt_motor_stopper1.stl

[📱 3Dビューアーで開く](stl/mobile_robot/tt_motor/tt_motor_stopper1.stl)

![tt_motor_stopper1](images/stl/mobile_robot/tt_motor/tt_motor_stopper1.jpg)

#### tt_motor_stopper2.stl

[📱 3Dビューアーで開く](stl/mobile_robot/tt_motor/tt_motor_stopper2.stl)

![tt_motor_stopper2](images/stl/mobile_robot/tt_motor/tt_motor_stopper2.jpg)

## pan

パンチルト機構のコンポーネント集です。

### mg996r

MG996Rサーボモーター用のパーツです。

#### pan_adapter.stl

[📱 3Dビューアーで開く](stl/pan/mg996r/pan_adapter.stl)

![pan_adapter](images/stl/pan/mg996r/pan_adapter.jpg)

#### pan_plate_top.stl

[📱 3Dビューアーで開く](stl/pan/mg996r/pan_plate_top.stl)

![pan_plate_top](images/stl/pan/mg996r/pan_plate_top.jpg)

#### pan_stand_left.stl

[📱 3Dビューアーで開く](stl/pan/mg996r/pan_stand_left.stl)

![pan_stand_left](images/stl/pan/mg996r/pan_stand_left.jpg)

#### pan_stand_right.stl

[📱 3Dビューアーで開く](stl/pan/mg996r/pan_stand_right.stl)

![pan_stand_right](images/stl/pan/mg996r/pan_stand_right.jpg)

## raspi

Raspberry Pi用のコンポーネント集です。

#### poll_25mm.stl

[📱 3Dビューアーで開く](stl/raspi/poll_25mm.stl)

![poll_25mm](images/stl/raspi/poll_25mm.jpg)

#### raspi_stand.stl

[📱 3Dビューアーで開く](stl/raspi/raspi_stand.stl)

![raspi_stand](images/stl/raspi/raspi_stand.jpg)

#### raspi_stopper1.stl

[📱 3Dビューアーで開く](stl/raspi/raspi_stopper1.stl)

![raspi_stopper1](images/stl/raspi/raspi_stopper1.jpg)

#### raspi_stopper2.stl

[📱 3Dビューアーで開く](stl/raspi/raspi_stopper2.stl)

![raspi_stopper2](images/stl/raspi/raspi_stopper2.jpg)

#### raspi_top_plate.stl

[📱 3Dビューアーで開く](stl/raspi/raspi_top_plate.stl)

![raspi_top_plate](images/stl/raspi/raspi_top_plate.jpg)

## smart_phone

スマートフォンマウントのコンポーネント集です。

#### cover_smartphone_base.stl

[📱 3Dビューアーで開く](stl/smart_phone/cover_smartphone_base.stl)

![cover_smartphone_base](images/stl/smart_phone/cover_smartphone_base.jpg)

#### smartphone_long_width_75_height_11.stl

[📱 3Dビューアーで開く](stl/smart_phone/smartphone_long_width_75_height_11.stl)

![smartphone_long_width_75_height_11](images/stl/smart_phone/smartphone_long_width_75_height_11.jpg)

#### smartphone_short_width_37_height_11.stl

[📱 3Dビューアーで開く](stl/smart_phone/smartphone_short_width_37_height_11.stl)

![smartphone_short_width_37_height_11](images/stl/smart_phone/smartphone_short_width_37_height_11.jpg)

## template

テンプレートおよび汎用パーツです。

#### cover_back_depth_5_template.stl

[📱 3Dビューアーで開く](stl/template/cover_back_depth_5_template.stl)

![cover_back_depth_5_template](images/stl/template/cover_back_depth_5_template.jpg)

#### cover_back_template.stl

[📱 3Dビューアーで開く](stl/template/cover_back_template.stl)

![cover_back_template](images/stl/template/cover_back_template.jpg)

#### cover_template.stl

[📱 3Dビューアーで開く](stl/template/cover_template.stl)

![cover_template](images/stl/template/cover_template.jpg)



