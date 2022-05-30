# Car dealer

## Model: Cars

## table: Car

- id :                             bigint                  PRIMARYKEY(NOTNULL, AUTOINCREMENTS, UNIQUE)
- frame_number :                   CHAR(17)                NULL, UNIQUE, INDEX
- poster :                         VARCHAR(255)            NULL
- brand :                          VARCHAR(100)            NOTNULL, INDEX
- category :                       VARCHAR(50)             NOTNULL, INDEX
- model :                          VARCHAR(100)            NOTNULL, INDEX
- year_model :                     YEAR                    NOTNULL, INDEX
- places :                         TINYINT                 NOTNULL, INDEX
- doors :                          TINYINT                 NOTNULL
- color :                          VARCHAR(20)             NOTNULL, INDEX
- km_done :                        MEDIUMINT               NOTNULL, INDEX  
- altezza :                        FLOAT(5,2)              NULL
- larghezza :                      FLOAT(5,2)              NULL
- lunghezza :                      FLOAT(5,2)              NULL
- description :                    TEXT                    NULL
- reservoir :                      VARCHAR(20)             NOTNULL, INDEX
- revised :                        TINYINT                 NOTNULL, INDEX
- purchase_price :                 DECIMAL(8,2)            NOTNULL  
- price :                          DECIMAL(8,2)            NOTNULL 
- discount :                       FLOAT(3,1)              NULL
- special_price :                  DECIMAL(8,2)            NULL 
- crash_test_euro_vote :           FLOAT(3,1)              NULL
- consumption_over_100_km :        VARCHAR(5)              NULL
- radio :                          TINYINT                 NOTNULL DEFAULT(1)
- Bluetooth :                      TINYINT                 NOTNULL DEFAULT(0)
- air_conditioning :               TINYINT                 NOTNULL DEFAULT(1)
- Power_steering :                 TINYINT                 NULL 
- Front_seats_armrest :            TINYINT                 NULL 
- lateral_airbag :                 TINYINT                 NOTNULL DEFAULT(1)
- head_airbag :                    TINYINT                 NOTNULL DEFAULT(1)
- front_head_restraints :          TINYINT                 NOTNULL DEFAULT(0)
- turn_assist :                    TINYINT                 NULL, INDEX 
- Automatic_emergency_braking :    TINYINT                 NULL
- in_stock :                       DATE                    NULL, INDEX



