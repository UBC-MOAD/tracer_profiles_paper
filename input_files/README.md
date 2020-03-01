## Input files

Follow the links to download the binary files of initial temperature, salinity and tracer 
concentration and bathymetry files required to run the model.

### Bathymetry 

Depth:

* [bathy_616x360_AstoriaLike03.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/bathymetry/bathy_616x360_AstoriaLike03.bin) - `bathyFile` in data file, runs AST 01 and AST 03 (Canyon bathymetry) 
* [bathy_616x360_AstoriaLike03_NoCny.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/bathymetry/bathy_616x360_AstoriaLike03_NoCny.bin) - `bathyFile` in data file, runs AST 02 and AST 04 (No-canyon bathymetry) 
* [bathy_616x360_BarkleyLike03.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/bathymetry/bathy_616x360_BarkleyLike03.bin) - `bathyFile` in data file, runs BAR 01 and BAR 03 (Canyon bathymetry) 
* [bathy_616x360_BarkleyLike03_NoCny.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/bathymetry/bathy_616x360_BarkleyLike03_NoCny.bin) - `bathyFile` in data file, runs BAR 02 and BAR 04 (No-canyon bathymetry) 

Associated grid spacing files:

* [delx_616x360_AstoriaLike03.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/bathymetry/delx_616x360_AstoriaLike03.bin)
* [dely_616x360_AstoriaLike03.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/dely_616x360_AstoriaLike03.bin)
* [delx_616x360_AstoriaLike03_NoCny.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/delx_616x360_AstoriaLike03_NoCny.bin)
* [dely_616x360_AstoriaLike03_NoCny.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/dely_616x360_AstoriaLike03_NoCny.bin)
* [delx_616x360_BarkleyLike03.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/delx_616x360_BarkleyLike03.bin)
* [dely_616x360_BarkleyLike03.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/dely_616x360_BarkleyLike03.bin)
* [delx_616x360_BarkleyLike03_NoCny.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/delx_616x360_BarkleyLike03_NoCny.bin)
* [dely_616x360_BarkleyLike03_NoCny.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/dely_616x360_BarkleyLike03_NoCny.bin)

### Stratification
        
* [Linsal_N5p5_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Linsal_N5p5_104zlev_616x360.bin) - Salinity for AST and BAR, runs 01 and 02 (linear).
* [Lintmp_N5p5_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Lintmp_N5p5_104zlev_616x360.bin) - Temperature for AST and BAR, runs 01 and 02 (linear).
* [Ast_sal_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Ast_sal_104zlev_616x360.bin) - Salinity for AST, runs 03 and 04 (ARGO).
* [Ast_tmp_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Ast_tmp_104zlev_616x360.bin) - Temperature for AST, runs 03 and 04 (ARGO).
* [Barkley_SalB_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_SalB_104zlev_616x360.bin) - Salinity for BAR, runs 03 and 04 (Pathways).
* [Barkley_Tmp_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_Tmp_104zlev_616x360.bin) - Temperature for BAR, runs 03 and 04 (Pathways).
  
### Tracer Profiles

* [Linnit104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Linnit90zlev_616x360.bin) - `PTRACERS_initialFile(1)` in data.ptracers. 
* [Barkley_sal_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_sal_104zlev_616x360.bin) - `PTRACERS_initialFile(2)` in data.ptracers. 
* [Barkley_oxy_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_oxy_104zlev_616x360.bin) - Dissolved oxygen `PTRACERS_initialFile(3)` in data.ptracers. 
* [Barkley_nit_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_nit_104zlev_616x360.bin) - Nitrate `PTRACERS_initialFile(4)` in data.ptracers. 
* [Barkley_sil_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_sil_104zlev_616x360.bin) - Dissolved silicate `PTRACERS_initialFile(5)` in data.ptracers. 
* [Barkley_pho_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_pho_104zlev_616x360.bin) - Phosphate `PTRACERS_initialFile(6)` in data.ptracers. 
* [LineCSep2013_nox_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/LineCSep2013_nox_104zlev_616x360.bin) - Nitrous-oxide `PTRACERS_initialFile(7)` in data.ptracers. 
* [LineCSep2013_met_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/LineCSep2013_met_104zlev_616x360.bin) - Methane `PTRACERS_initialFile(8)` in data.ptracers. 
* [Barkley_DIC_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_DIC_104zlev_616x360.bin) - DIC `PTRACERS_initialFile(9)` in data.ptracers. 
* [Barkley_Alk_104zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_profiles_paper/input_files/stratification/Barkley_Alk_104zlev_616x360.bin) - Total alkalinity `PTRACERS_initialFile(10)` in data.ptracers. 


