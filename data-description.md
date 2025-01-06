#### Columns Desc, data type, usefulness, observations
```sh
Make - Brand, category
Model - Model of vehicle, category
MakeCode - same as Make, category, useful
FamilyCode - same as Model, category, useful
YearGroup - Manufacture Year?, datetime, useful
MonthGroup - Manufacture Month?, datetime
SequenceNum - ??
Description - VE Omega Sedan 4dr. Auto 4sp 3.6i
CurrentRelease - Current release, boolean, all are False
ImportFlag - Is is imported ? L-Local, not useful for now
LimitedEdition - True/False, boolean
Series - same car model has different series
SeriesModelYear - MY12(Model Year 2012) can combine with Series
BadgeDescription - car badge? maynot useful
BadgeSecondaryDescription - moore car badge? maynot useful
BodyStyleDescription - Sedan/Van, category, useful
BodyConfigDescription - ??, maynot useful
WheelBaseConfig - useful, but missing alot data
Roofline - High/Low Roof, maynot useful, only Bus/Van/Cab has this feature
ExtraIdentification - maynot useful
DriveDescription - shared same info as DriveCode
DriveCode - RWD/4X4, useful
GearTypeDescription - Automatic/Manual, category, useful
GearLocationDescription - Floor/Dash, 93% are floor, maybe useful
GearNum - 1-9 Gears, useful
DoorNum - useful
EngineSize - shared same info as EngineDescription
EngineDescription - 2.4/3.6, useful
Cylinders - 4-10 cyclinders, useful
FuelTypeDescription - useful
InductionDescription - Aspirated/Turbo, useful
OptionCategory - ??
CamDescription - ??
EngineTypeDescription - ??
FuelCapacity - int, useful
FuelDeliveryDescription - ??
MethodOfDeliveryDescription - ??
GrossCombinationMAss - int, maynot useful
GrossVehicleMass - int, maynot useful
VIN - vehicle identification number, unique, not useful
WheelBase - int, mayb useful
Height - int, mayb useful
Length - int, mayb useful
Width - int, mayb useful
KerbWeight - int, mayb useful
TareMass - weight of an empty venhicle, int, mayb useful
PayLoad -
Power -
PowerRPMFrom -
PowerRPMTo -
Torque -
TorqueRPMFrom -
TorqueRPMTo -
RonRating -
SeatCapacity -
ModelCode -
BuildCountryOriginDescription - JAPAN/AUSTRALIA, useful
ValvesCylinder -
EngineCycleDescription -
EngineConfigurationDescription -
EngineLocation -
EngineNum - eg: HBA04 ######, engine id
Acceleration -
FrontTyreSize -
RearTyreSize -
FrontRimDesc -
RearRimDesc -
TowingBrakes -
TowingNoBrakes -
WarrantyCustAssist -
FreeScheduledService -
WarrantyYears - warrant year left, int, useful
WarrantyKM - KM 
FirstServiceKM -
FirstServiceMonths -
RegServiceMonths -
AltEngEngineType -
AltEngBatteryType -
AltEngCurrentType -
AltEngAmpHours -
AltEngVolts -
AltEngChargingMethod -
AltEngPower -
AltEngPowerFrom -
AltEngPowerTo -
AltEngTorque -
AltEngTorqueFrom -
AltEngTorqueTo -
AltEngDrive -
NormalChargeMins -
QuickChargeMins -
NormalChargeVoltage -
QuickChargeVoltage -
KMRangeElectricEng -
ElectricEngineLocation -
TopSpeedElectricEng -
GreenhouseRating -
AirpollutionRating -
OverallGreenStarRating -
CO2Combined -
CO2Urban -
CO2ExtraUrban -
FuelUrban - fuel efficiency in city driving, float
FuelExtraurban - fuel efficiency in open roads, such as motorways and A roads, at higher speeds.
FuelCombined -
EmissionStandard -
MaxEthanolBlend -
AncapRating -
VFactsClass -
VFactsSegment -
VFactsPrice -
IsPPlateApproved - provisional licence?, True/False, boolean
AverageKM -
GoodKM -
NewPrice -
Colour -
Branch - 
SaleCategory - useful
Sold_Date - not useful
Compliance_Date - ??
Age_Comp_Months - ??
KM - driven mileage
Sold_Amount - dependent variable, float
```