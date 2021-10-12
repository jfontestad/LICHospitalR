# LICHospitalR 0.2.0
* Added a temendous amount of functionality

# LICHospitalR 0.1.0
* Added the following functions
1. infection_prevention_patient_days_automation()
2. infection_prevention_patient_days_tbl()
3. infection_prevention_pateint_days_query()
4. orsos_j_accounts_automation()
5. orsos_j_accounts_query()
6. weekly_psy_discharges_query()
7. weekly_psy_discharges_automation()
8. monthly_psy_admits_discharges_tbl()
9. monthly_psy_admits_query()
10. monthly_psy_discharges_query()
11. monthly_psy_admits_discharges_automation()
12. myhealth_monthly_surgery_query()
13. myhealth_monthly_surgery_tbl()
14. myhealth_monthly_surgery_automation()
15. monthly_trauma_tbl()
16. monthly_trauma_automation()
17. monthly_admit_trauma_query()
18. monthly_discharge_trauma_query()
* All automation functions gained the following parameters
1. .delete_file
2. .email

## LICHospitalR 0.0.0.9006
* Added trauma functions and orsos to sproc functionality
* Started separating automations apart to a more consistent workflow of:
Query -> Table Data Function -> Automation (The emailing)

## LICHospitalR 0.0.0.9005
* Complete package site redesign and addition of some automations
1. geocode_discharges_automation()
2. code64_automation()
3. congenital_malformation_automation()
4. congenital_malformation_query()
5. discharge_order_to_discharge_automation()
6. discharge_order_to_discharge_query()
7. duplicate_coded_cataracts_automation()
8. duplicate_coded_cataracts_query()
9. inpatient_coding_lag_automation()
10. inpatient_coding_lag_query()
11. inpatient_coding_lag_tbl()
12. orsos_to_sproc_automation()
13. orsos_to_sproc_query()

## LICHospitalR 0.0.0.9004
* Added teh following functions:
1. Added geocode_discharges_automatic()

## LICHospitalR 0.0.0.9003
* Update los_ra_indes_summary_tbl() to use los_var = base::abs(1-los_index) + base::abs(1-rar_index)
* Added the following functions:
1. denials_admits_by_ed_query
2. denials_admits_by_md_query
3. denials_inpatient_query
4. denials_outpatient_query
5. coded_consults_query
6. coded_consults_seasonal_diagnostics
7. coded_consults_top_plt
8. coded_consults_trend_plt
9. coded_consults_top_providers
10. query_pract_dim_v
* Made Coded Consults Vignette

## LICHopspitalR 0.0.0.9002
* Added the following functions:
1. db_connect
2. db_disconnect
3. los_ra_index_query
4. los_ra_index_summary_tbl
5. los_ra_index_plt
6. opt_bin

## LICHospitalR 0.0.0.9001
* Added first set of functions

## LICHosptalR 0.0.0.9000

* Added a `NEWS.md` file to track changes to the package.
