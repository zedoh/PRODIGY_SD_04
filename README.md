# Suduko Solver
- It is a sudoku solver gui game made using **SFML**, **C++**
- [Backtracking Algorithm](https://en.wikipedia.org/wiki/Backtracking) is used to solve the sudoku grid.

# TEST
[![](https://mermaid.ink/img/pako:eNqNVtmO2jwUfhUrF1XoAAMJZcll6arOSNXQ9pcqpMokDlgEO7IdBjqCZ_-PHTuEZSgXiOQ7--IvfvFinhAv8uIMS_mB4rnAqymbFAlfFp8FTdDbVmtMsuwI463WhGdrIuooKL4vlOLMgQAcpFOAGV4RmeOYoJ9fX6bMhETaObwghFpojbOCoAhRpiyy4BCFJIDNOM8smNLNKSQXONeWMo2iJxIrzOYZmWjQKiiyUcgq6GedDwjuTHy_Fhg1UcrhL0IxZ1IZg08AvAFBziVVlLMj4S8Ix0WQagVJ_2o3acaxatgAkqhf2n09SE32pazQP660pvDJVFtZ16WQhMKUST_n9CTlKqsGMialyNrNrVe_cVFWptsw3aiLEoGf_WfKEv5ctZolRPxnIIhUhrfaPyURP6DTY55xAd6mbOdmXu5JOXXQnJnX16cHKhmekcxq_DDjK3EzKovrKTkcRlzTLgSx80Z3ZWzf7EPVMJVEkVSCsjnSY_x-45wvCJtIbXNy2XPDpjAmTBFRJvKAZxn02kp0h22CV_pslc3mWO1HXkji0r6QGNVWO92EcgKHg2mn0EIxHASp4-mU18Zsf_YM5wyW9E-uxF4fnP1-78yrIToSKOFxRrBNspIhJ_wMhDBRWJEzswfKyFkyZ9txiD4hGUhI8mRaphf3VAJreCKRhsIAdFxWwnoGk2I2h978e9mrtap11L_MH25sNx4jp73ALMmIme8jDHwFu4P8VX3cR6HWtXmfORhnNF5qMlm9ti4H87L1OaZiD01rwm9_7PEb2c44Fsl3QaQELlmS7cc1MZVrT-Y5ir45tIk2FcFuo4oDwV05eZvbldIOq3xgfk3ghw1zPh7_6eNwGJEemWE86TdeXX5dflV_DsdZOZMqjQWJl3r9fL05V86RcaVJRLhdPalHO4JtLVbsdl-x2-4Lvuwy3-5MKizU4SRZYHwlhO7he5JyQfRZ0mR3WzDnyjDT7viO8MDnNK6uCeUZhdc7ROUf-BjCObMhakx7td1VOUv75KLflVSAfEeBt3isO4yrr_rOlnHMsxXHSvOqKad2MSpFrxKCU7Cs4vikorFN7cIEr1v3ekxM_ol5bf-h4w-c5zd8cdBTwfTG77ymtyJihWkCV0dT3dRTCyCnqRfBY0JSXGRq6hmJUceF4pMti71IiYI0vSJPgPfthdOLUpzJCv2YUOhzBcJlClLxohdPf1oh4JxKBS5hSimda7wQGcALpXIZ3d9rcXtO1aKYtWO-upc0ga-WWqxH_ft-0B_iICT9QYjfhWESz7qjYRr0umky6HQD7O12TS_HTHvdeFHQ6bd7w85w1AnCoNcfves3va0XDdrhcBh0BmFvFHQ6YTgAo7-cQx2d9ijod7uDUTAMh_1RtzdqesSU82jv2frPhPhtDEyNu_8Bea_Tgg?type=png)](https://mermaid.live/edit#pako:eNqNVtmO2jwUfhUrF1XoAAMJZcll6arOSNXQ9pcqpMokDlgEO7IdBjqCZ_-PHTuEZSgXiOQ7--IvfvFinhAv8uIMS_mB4rnAqymbFAlfFp8FTdDbVmtMsuwI463WhGdrIuooKL4vlOLMgQAcpFOAGV4RmeOYoJ9fX6bMhETaObwghFpojbOCoAhRpiyy4BCFJIDNOM8smNLNKSQXONeWMo2iJxIrzOYZmWjQKiiyUcgq6GedDwjuTHy_Fhg1UcrhL0IxZ1IZg08AvAFBziVVlLMj4S8Ix0WQagVJ_2o3acaxatgAkqhf2n09SE32pazQP660pvDJVFtZ16WQhMKUST_n9CTlKqsGMialyNrNrVe_cVFWptsw3aiLEoGf_WfKEv5ctZolRPxnIIhUhrfaPyURP6DTY55xAd6mbOdmXu5JOXXQnJnX16cHKhmekcxq_DDjK3EzKovrKTkcRlzTLgSx80Z3ZWzf7EPVMJVEkVSCsjnSY_x-45wvCJtIbXNy2XPDpjAmTBFRJvKAZxn02kp0h22CV_pslc3mWO1HXkji0r6QGNVWO92EcgKHg2mn0EIxHASp4-mU18Zsf_YM5wyW9E-uxF4fnP1-78yrIToSKOFxRrBNspIhJ_wMhDBRWJEzswfKyFkyZ9txiD4hGUhI8mRaphf3VAJreCKRhsIAdFxWwnoGk2I2h978e9mrtap11L_MH25sNx4jp73ALMmIme8jDHwFu4P8VX3cR6HWtXmfORhnNF5qMlm9ti4H87L1OaZiD01rwm9_7PEb2c44Fsl3QaQELlmS7cc1MZVrT-Y5ir45tIk2FcFuo4oDwV05eZvbldIOq3xgfk3ghw1zPh7_6eNwGJEemWE86TdeXX5dflV_DsdZOZMqjQWJl3r9fL05V86RcaVJRLhdPalHO4JtLVbsdl-x2-4Lvuwy3-5MKizU4SRZYHwlhO7he5JyQfRZ0mR3WzDnyjDT7viO8MDnNK6uCeUZhdc7ROUf-BjCObMhakx7td1VOUv75KLflVSAfEeBt3isO4yrr_rOlnHMsxXHSvOqKad2MSpFrxKCU7Cs4vikorFN7cIEr1v3ekxM_ol5bf-h4w-c5zd8cdBTwfTG77ymtyJihWkCV0dT3dRTCyCnqRfBY0JSXGRq6hmJUceF4pMti71IiYI0vSJPgPfthdOLUpzJCv2YUOhzBcJlClLxohdPf1oh4JxKBS5hSimda7wQGcALpXIZ3d9rcXtO1aKYtWO-upc0ga-WWqxH_ft-0B_iICT9QYjfhWESz7qjYRr0umky6HQD7O12TS_HTHvdeFHQ6bd7w85w1AnCoNcfves3va0XDdrhcBh0BmFvFHQ6YTgAo7-cQx2d9ijod7uDUTAMh_1RtzdqesSU82jv2frPhPhtDEyNu_8Bea_Tgg)
# Preview
https://github.com/zedoh/PRODIGY_SD_04/assets/48362347/8d05a63d-8e5b-40de-9db8-54c82859153b
# Controls
- `Left click` on the cell to change or give a value.
- `Left click` + `DEL` to delete a value
- `ESC` to close the game
