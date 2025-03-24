# Lawrence Berkeley National Lab Dataset (LBNL59)

Data source: LBNL59

Duration: 2020-08-01 00:00:00 -- 2021-01-01 00:00:00

Sampling frequency: 15min

Each heatmap is plotted after resampling and outlier removal.

## Error Report
Below points own meter records but not in the LBNL Brick model:
- rtu_*_sat_sp_tn (\*: 001, 002, 003, 004)
- rtu_*_oa_temp (\*: 001, 002, 003, 004)
- rtu_*_fltrd_sa_flow_tn (\*: 001, 002, 003, 004)
- rtu_*_oa_flow_tn (\*: 001, 002, 003, 004)
- rtu_*_oadmpr_pct (\*: 001, 002, 003, 004)

## Heatmap
### Zone-level Data
![zone heating setpoints](./heatmap/zone_*_heating_sp.png)
![zone cooling setpoints](./heatmap/zone_*_cooling_sp.png)
Zone temperature of interior zone [cerc_templogger_*]: Unit probably wrong, possible be °C.
![zone cooling setpoints](./heatmap/cerc_templogger_*.png)
![zone cooling setpoints](./heatmap/zone_*_temp.png)
![zone cooling setpoints](./heatmap/zone_*_co2.png)
![zone heating setpoints](./heatmap/zone_*_fan_spd.png)
![zone heating setpoints](./heatmap/zone_*_hw_valve.png)

### AHU-level Data
![zone heating setpoints](./heatmap/rtu_*_sat_sp_tn.png)
![zone heating setpoints](./heatmap/rtu_*_sa_temp.png)
![zone heating setpoints](./heatmap/rtu_*_ra_temp.png)
![zone heating setpoints](./heatmap/rtu_*_ma_temp.png)
![zone heating setpoints](./heatmap/rtu_*_oa_temp.png)
![zone heating setpoints](./heatmap/rtu_*_fltrd_sa_flow_tn.png)
![zone heating setpoints](./heatmap/rtu_*_oa_flow_tn.png)
![zone heating setpoints](./heatmap/rtu_*_oadmpr_pct.png)
![zone heating setpoints](./heatmap/rtu_*_econ_stpt_tn.png)
![zone heating setpoints](./heatmap/rtu_*_pa_static_stpt_tn.png)
![zone heating setpoints](./heatmap/rtu_*_fltrd_**_plenum_press_tn.png)
![zone heating setpoints](./heatmap/rtu_*_sf_vfd_spd_fbk_tn.png)
![zone heating setpoints](./heatmap/rtu_*_rf_vfd_spd_fbk_tn.png)
