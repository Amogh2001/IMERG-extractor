# IMERG-extractor
Extracts and classifies IMERG .nc file data into months and years

Example:

rain_data = Rainfall_Year('Year_IMERG_2001.nc', leap = False)
rain_data.month_imerg_getter()
rain_data01 = np.array(rain_data.r_imerg_arr)
rain_arr = np.array(rain_data01)

where,

'Year_IMERG_2001' is the IMERG file

'month_imerg_getter()' is a function that returns the monthly rain

'r_imerg_arr' stores this data
