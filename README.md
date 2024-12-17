# dynare-model-language

This is a Visual Studio Code extension for the Dynare model language. It provides syntax highlighting for the Dynare model language.

## Release Notes

### 0.1.1

Added support for preprocessor blocks and updated the list of highlighted keywords:
 * bvar_density
 * bvar_forecast
 * bvar_irf
 * calib_smoother
 * calibration
 * chain
 * change_type
 * check
 * coeff
 * coefficients
 * compilation_setup
 * conditional_forecast
 * conditional_forecast_paths
 * constant_simulation_length
 * data
 * deterministic_trends
 * diagonal_only
 * discretionary_policy
 * dsample
 * duration
 * dynare_sensitivity
 * dynasave
 * dynatype
 * end
 * endval
 * equations
 * estimated_params
 * estimated_params_bounds
 * estimated_params_init
 * estimated_params_remove
 * estimation
 * evaluate_planner_objective
 * exclusion
 * extended_path
 * external_function
 * filter_initial_state
 * filtered_theoretical_moments_grid
 * forecast
 * generate_irfs
 * heterogeneity_dimension
 * heteroskedastic_shocks
 * histval
 * histval_file
 * homotopy_setup
 * identification
 * init2shocks
 * initial_condition_decomposition
 * initval
 * initval_file
 * irf_calibration
 * irf_plot_threshold
 * lag
 * learnt_in 
 * load_params_and_steady_state
 * log_trend_var
 * lower_cholesky
 * markov_switching
 * matched_irfs
 * matched_irfs_weights
 * matched_moments
 * method_of_moments
 * mh_initialize_from_previous_mcmc
 * mh_initialize_from_previous_mcmc_directory
 * mh_initialize_from_previous_mcmc_prior
 * mh_initialize_from_previous_mcmc_record
 * mh_recover
 * model_comparison
 * model_diagnostics
 * model_info
 * model_local_variable
 * model_options
 * model_remove
 * model_replace
 * moment_calibration
 * ms_compute_mdd
 * ms_compute_probabilities
 * ms_estimation
 * ms_forecast
 * ms_irf
 * ms_simulation
 * ms_variance_decomposition
 * mshocks
 * no_homotopy
 * number_of_lags
 * number_of_regimes
 * observation_trends
 * occbin_constraints
 * occbin_graph
 * occbin_setup
 * occbin_solver
 * occbin_write_regimes
 * optim_weights
 * osr
 * osr_params
 * osr_params_bounds
 * overwrite
 * pac_model
 * pac_target_info
 * parameters
 * particle_filter_options
 * perfect_foresight_setup
 * perfect_foresight_solver
 * perfect_foresight_with_expectation_errors_setup
 * perfect_foresight_with_expectation_errors_solver
 * planner_discount
 * planner_discount_latex_name
 * planner_objective
 * plot_conditional_forecast
 * plot_shock_decomposition
 * predetermined_variables
 * priors
 * qz_criterium
 * qz_zero_threshold
 * ramsey_constraints
 * ramsey_model
 * ramsey_policy
 * realtime_shock_decomposition
 * resid
 * rplot
 * save_params_and_steady_state
 * sbvar
 * sensitivity
 * series
 * set_time
 * shock_decomposition
 * shock_groups
 * shocks
 * simul
 * simul_replic
 * simul_seed
 * smoother2histval
 * squeeze_shock_decomposition
 * stderr_multiples
 * steady
 * stoch_simul
 * structural
 * svar
 * svar_global_identification_check
 * svar_identification
 * time_shift
 * trend_component_model
 * trend_var
 * unit_root_vars
 * upper_cholesky
 * var
 * var_expectation_model
 * var_model
 * var_remove
 * varexo
 * varexo_det
 * varexobs
 * variances
 * varobs
 * write_latex_dynamic_model
 * write_latex_original_model
 * write_latex_static_model
 * write_latex_steady_state_model
 * xls_range
 * xls_sheet

### 0.1.0

Initial release, with support for the following Dynare model language keywords:
 * var
 * varexo
 * varexo_det
 * trend_var
 * log_trend_var
 * predetermined_variables
 * parameters
 * model_local_variable
 * heterogeneity_dimension
 * model_info
 * estimation
 * set_time
 * data
 * varobs
 * varexobs
 * unit_root_vars
 * rplot
 * osr_params
 * osr
 * dynatype
 * dynasave
 * model_comparison
 * change_type
 * load_params_and_steady_state
 * save_params_and_steady_state
 * write_latex_dynamic_model
 * write_latex_static_model
 * write_latex_original_model
 * write_latex_steady_state_model
 * steady
 * check
 * simul
 * stoch_simul
 * var_model
 * trend_component_model
 * var_expectation_model
 * pac_model
 * dsample
 * planner_objective
 * ramsey_model
 * ramsey_policy
 * evaluate_planner_objective
 * occbin_setup
 * occbin_solver
 * occbin_write_regimes
 * occbin_graph
 * discretionary_policy
 * identification
 * bvar_density
 * bvar_forecast
 * bvar_irf
 * sensitivity
 * dynare_sensitivity
 * initval_file
 * histval_file
 * forecast
 * shock_decomposition
 * realtime_shock_decomposition
 * plot_shock_decomposition
 * initial_condition_decomposition
 * squeeze_shock_decomposition
 * sbvar
 * ms_estimation
 * ms_simulation
 * ms_compute_mdd
 * ms_compute_probabilities
 * ms_forecast
 * ms_irf
 * ms_variance_decomposition
 * conditional_forecast
 * plot_conditional_forecast
 * method_of_moments
 * markov_switching
 * svar
 * svar_global_identification_check
 * external_function
 * calib_smoother
 * model_diagnostics
 * extended_path
 * smoother2histval
 * perfect_foresight_setup
 * perfect_foresight_solver
 * perfect_foresight_with_expectation_errors_setup
 * perfect_foresight_with_expectation_errors_solver
 * compilation_setup
 * AIM_SOLVER
 * ANALYTIC_DERIVATION
 * ANALYTIC_DERIVATION_MODE
 * AR
 * POSTERIOR_SAMPLING_METHOD
 * BALANCED_GROWTH_TEST_TOL
 * BAYESIAN_IRF
 * BETA_PDF
 * BLOCK
 * USE_CALIBRATION
 * SILENT_OPTIMIZER
 * BVAR_DENSITY
 * BVAR_FORECAST
 * BVAR_IRF
 * NODECOMPOSITION
 * DR_DISPLAY_TOL
 * HUGE_NUMBER
 * FIG_NAME
 * WRITE_XLS
 * BVAR_PRIOR_DECAY
 * BVAR_PRIOR_FLAT
 * BVAR_PRIOR_LAMBDA
 * INTERACTIVE
 * SCREEN_SHOCKS
 * STEADYSTATE
 * BVAR_PRIOR_MU
 * BVAR_PRIOR_OMEGA
 * BVAR_PRIOR_TAU
 * BVAR_PRIOR_TRAIN
 * DETAIL_PLOT
 * TYPE
 * BVAR_REPLIC
 * BYTECODE
 * ALL_VALUES_REQUIRED
 * PROPOSAL_DISTRIBUTION
 * REALTIME
 * VINTAGE
 * CALIB_SMOOTHER
 * CHANGE_TYPE
 * CHECK
 * CONDITIONAL_FORECAST
 * CONDITIONAL_FORECAST_PATHS
 * CONF_SIG
 * CONSTANT
 * CONTROLLED_VAREXO
 * CORR
 * CUTOFF
 * CYCLE_REDUCTION
 * LOGARITHMIC_REDUCTION
 * COMMA
 * CONSIDER_ALL_ENDOGENOUS
 * CONSIDER_ALL_ENDOGENOUS_AND_AUXILIARY
 * CONSIDER_ONLY_OBSERVED
 * INITIAL_CONDITION_DECOMPOSITION
 * DATAFILE
 * FILE
 * SERIES
 * DOUBLING
 * DR_CYCLE_REDUCTION_TOL
 * DR_CYCLE_REDUCTION_MAXITER
 * DR_LOGARITHMIC_REDUCTION_TOL
 * DR_LOGARITHMIC_REDUCTION_MAXITER
 * DR_ALGO
 * DROP
 * DSAMPLE
 * DYNASAVE
 * DYNATYPE
 * CALIBRATION
 * DIFFERENTIATE_FORWARD_VARS
 * END
 * ENDVAL
 * EQUAL
 * ESTIMATION
 * ESTIMATED_PARAMS
 * ESTIMATED_PARAMS_BOUNDS
 * ESTIMATED_PARAMS_INIT
 * EXTENDED_PATH
 * ENDOGENOUS_PRIOR
 * EXPRESSION
 * FILENAME
 * DIRNAME
 * FILTER_STEP_AHEAD
 * FILTERED_VARS
 * FIRST_OBS
 * FIRST_SIMULATION_PERIOD
 * LAST_SIMULATION_PERIOD
 * LAST_OBS
 * SET_TIME
 * OSR_PARAMS_BOUNDS
 * KEEP_KALMAN_ALGO_IF_SINGULARITY_IS_DETECTED
 * FALSE
 * FLOAT_NUMBER
 * DATE
 * DEFAULT
 * FIXED_POINT
 * FLIP
 * OPT_ALGO
 * COMPILATION_SETUP
 * COMPILER
 * ADD_FLAGS
 * SUBSTITUTE_FLAGS
 * ADD_LIBS
 * SUBSTITUTE_LIBS
 * FORECAST
 * K_ORDER_SOLVER
 * INSTRUMENTS
 * SHIFT
 * MEAN
 * STDEV
 * VARIANCE
 * MODE
 * INTERVAL
 * SHAPE
 * DOMAINN
 * GAMMA_PDF
 * GRAPH
 * GRAPH_FORMAT
 * CONDITIONAL_VARIANCE_DECOMPOSITION
 * NOCHECK
 * STD
 * HISTVAL
 * HISTVAL_FILE
 * HOMOTOPY_SETUP
 * HOMOTOPY_MODE
 * HOMOTOPY_STEPS
 * HOMOTOPY_FORCE_CONTINUE
 * HP_FILTER
 * HP_NGRID
 * FILTERED_THEORETICAL_MOMENTS_GRID
 * HYBRID
 * ONE_SIDED_HP_FILTER
 * IDENTIFICATION
 * INF_CONSTANT
 * INITVAL
 * INITVAL_FILE
 * BOUNDS
 * JSCALE
 * INIT
 * INFILE
 * INVARS
 * INT_NUMBER
 * CONDITIONAL_LIKELIHOOD
 * INV_GAMMA_PDF
 * INV_GAMMA1_PDF
 * INV_GAMMA2_PDF
 * IRF
 * IRF_SHOCKS
 * IRF_PLOT_THRESHOLD
 * IRF_CALIBRATION
 * FAST_KALMAN_FILTER
 * KALMAN_ALGO
 * KALMAN_TOL
 * DIFFUSE_KALMAN_TOL
 * SCHUR_VEC_TOL
 * SUBSAMPLES
 * OPTIONS
 * TOLF
 * TOLX
 * PLOT_INIT_DATE
 * PLOT_END_DATE
 * LAPLACE
 * LIK_INIT
 * LINEAR
 * LINEAR_DECOMPOSITION
 * LOAD_IDENT_FILES
 * LOAD_MH_FILE
 * LOAD_RESULTS_AFTER_LOAD_MH
 * LOAD_PARAMS_AND_STEADY_STATE
 * LOGLINEAR
 * LOGDATA
 * LYAPUNOV
 * LINEAR_APPROXIMATION
 * LYAPUNOV_COMPLEX_THRESHOLD
 * LYAPUNOV_FIXED_POINT_TOL
 * LYAPUNOV_DOUBLING_TOL
 * LOG_DEFLATOR
 * LOG_TREND_VAR
 * LOG_GROWTH_FACTOR
 * MATCHED_MOMENTS
 * MARKOWITZ
 * MARGINAL_DENSITY
 * MAX
 * MAXIT
 * MH_CONF_SIG
 * MH_DROP
 * MH_INIT_SCALE
 * MH_INIT_SCALE_FACTOR
 * MH_JSCALE
 * MH_TUNE_JSCALE
 * MH_TUNE_GUESS
 * MH_POSTERIOR_MODE_ESTIMATION
 * MH_NBLOCKS
 * MH_REPLIC
 * MH_RECOVER
 * MH_INITIALIZE_FROM_PREVIOUS_MCMC
 * MH_INITIALIZE_FROM_PREVIOUS_MCMC_DIRECTORY
 * MH_INITIALIZE_FROM_PREVIOUS_MCMC_RECORD
 * MH_INITIALIZE_FROM_PREVIOUS_MCMC_PRIOR
 * POSTERIOR_MAX_SUBSAMPLE_DRAWS
 * MIN
 * MINIMAL_SOLVING_PERIODS
 * MODE_CHECK
 * MODE_CHECK_NEIGHBOURHOOD_SIZE
 * MODE_CHECK_SYMMETRIC_PLOTS
 * MODE_CHECK_NUMBER_OF_POINTS
 * MODE_COMPUTE
 * MODE_FILE
 * MODEL
 * MODEL_COMPARISON
 * MODEL_INFO
 * MSHOCKS
 * ABS
 * SIGN
 * MODEL_DIAGNOSTICS
 * MODIFIEDHARMONICMEAN
 * MOMENTS_VARENDO
 * CONTEMPORANEOUS_CORRELATION
 * DIFFUSE_FILTER
 * SUB_DRAWS
 * TAPER_STEPS
 * GEWEKE_INTERVAL
 * RAFTERY_LEWIS_QRS
 * RAFTERY_LEWIS_DIAGNOSTICS
 * BROOKS_GELMAN_PLOTROWS
 * MCMC_JUMPING_COVARIANCE
 * MOMENT_CALIBRATION
 * NUMBER_OF_PARTICLES
 * RESAMPLING
 * SYSTEMATIC
 * GENERIC
 * RESAMPLING_THRESHOLD
 * RESAMPLING_METHOD
 * KITAGAWA
 * STRATIFIED
 * SMOOTH
 * CPF_WEIGHTS
 * AMISANOTRISTANI
 * MURRAYJONESPARSLOW
 * WRITE_EQUATION_TAGS
 * FILTER_INITIAL_STATE
 * NONLINEAR_FILTER_INITIALIZATION
 * FILTER_ALGORITHM
 * PROPOSAL_APPROXIMATION
 * CUBATURE
 * UNSCENTED
 * MONTECARLO
 * DISTRIBUTION_APPROXIMATION
 * NAME
 * USE_PENALIZED_OBJECTIVE_FOR_HESSIAN
 * INIT_STATE
 * FAST_REALTIME
 * RESCALE_PREDICTION_ERROR_COVARIANCE
 * GENERATE_IRFS
 * NAN_CONSTANT
 * NO_STATIC
 * NOBS
 * NOCONSTANT
 * NODISPLAY
 * NOCORR
 * NODIAGNOSTIC
 * NOFUNCTIONS
 * NO_HOMOTOPY
 * NOGRAPH
 * POSTERIOR_NOGRAPH
 * POSTERIOR_GRAPH
 * NOMOMENTS
 * NOMODELSUMMARY
 * NOPRINT
 * NORMAL_PDF
 * SAVE_DRAWS
 * MODEL_NAME
 * STDERR_MULTIPLES
 * DIAGONAL_ONLY
 * DETERMINISTIC_TRENDS
 * OBSERVATION_TRENDS
 * OPTIM
 * OPTIM_WEIGHTS
 * ORDER
 * OSR
 * OSR_PARAMS
 * MAX_DIM_COVA_GROUP
 * ADVANCED
 * OUTFILE
 * OUTVARS
 * OVERWRITE
 * DISCOUNT
 * PARALLEL_LOCAL_FILES
 * PARAMETERS
 * PARAMETER_SET
 * PARTIAL_INFORMATION
 * PERIODS
 * PERIOD
 * PLANNER_OBJECTIVE
 * PLOT_CONDITIONAL_FORECAST
 * PLOT_PRIORS
 * PREFILTER
 * PRESAMPLE
 * PERFECT_FORESIGHT_SETUP
 * PERFECT_FORESIGHT_SOLVER
 * NO_POSTERIOR_KERNEL_DENSITY
 * FUNCTION
 * PERFECT_FORESIGHT_WITH_EXPECTATION_ERRORS_SETUP
 * PERFECT_FORESIGHT_WITH_EXPECTATION_ERRORS_SOLVER
 * PRINT
 * PRIOR_MC
 * PRIOR_TRUNC
 * PRIOR_MODE
 * PRIOR_MEAN
 * POSTERIOR_MODE
 * POSTERIOR_MEAN
 * POSTERIOR_MEDIAN
 * MLE_MODE
 * PRUNING
 * PARTICLE_FILTER_OPTIONS
 * QUOTED_STRING
 * QZ_CRITERIUM
 * QZ_ZERO_THRESHOLD
 * DSGE_VAR
 * DSGE_VARLAG
 * DSGE_PRIOR_WEIGHT
 * TRUNCATE
 * PIPE_E
 * PIPE_X
 * PIPE_P
 * RELATIVE_IRF
 * REPLIC
 * SIMUL_REPLIC
 * RPLOT
 * SAVE_PARAMS_AND_STEADY_STATE
 * PARAMETER_UNCERTAINTY
 * TARGETS
 * SHOCKS
 * HETEROSKEDASTIC_SHOCKS
 * SHOCK_DECOMPOSITION
 * SHOCK_GROUPS
 * USE_SHOCK_GROUPS
 * SIMUL
 * SIMUL_ALGO
 * SIMUL_SEED
 * ENDOGENOUS_TERMINAL_PERIOD
 * SMOOTHER
 * SMOOTHER2HISTVAL
 * SQUARE_ROOT_SOLVER
 * STACK_SOLVE_ALGO
 * STEADY_STATE_MODEL
 * SOLVE_ALGO
 * SOLVER_PERIODS
 * ROBUST_LIN_SOLVE
 * STDERR
 * STEADY
 * STOCH_SIMUL
 * REGIMES
 * REGIME
 * REALTIME_SHOCK_DECOMPOSITION
 * CONDITIONAL
 * UNCONDITIONAL
 * TEX
 * RAMSEY_MODEL
 * RAMSEY_POLICY
 * RAMSEY_CONSTRAINTS
 * PLANNER_DISCOUNT
 * PLANNER_DISCOUNT_LATEX_NAME
 * DISCRETIONARY_POLICY
 * DISCRETIONARY_TOL
 * EVALUATE_PLANNER_OBJECTIVE
 * OCCBIN_SETUP
 * OCCBIN_SOLVER
 * OCCBIN_WRITE_REGIMES
 * OCCBIN_GRAPH
 * SIMUL_MAXIT
 * LIKELIHOOD_MAXIT
 * SMOOTHER_MAXIT
 * SIMUL_PERIODS
 * LIKELIHOOD_PERIODS
 * SMOOTHER_PERIODS
 * SIMUL_CURB_RETRENCH
 * LIKELIHOOD_CURB_RETRENCH
 * SMOOTHER_CURB_RETRENCH
 * SIMUL_CHECK_AHEAD_PERIODS
 * SIMUL_MAX_CHECK_AHEAD_PERIODS
 * SIMUL_RESET_CHECK_AHEAD_PERIODS
 * LIKELIHOOD_CHECK_AHEAD_PERIODS
 * LIKELIHOOD_MAX_CHECK_AHEAD_PERIODS
 * SMOOTHER_CHECK_AHEAD_PERIODS
 * SMOOTHER_MAX_CHECK_AHEAD_PERIODS
 * SIMUL_DEBUG
 * SMOOTHER_DEBUG
 * SIMUL_PERIODIC_SOLUTION
 * LIKELIHOOD_PERIODIC_SOLUTION
 * SMOOTHER_PERIODIC_SOLUTION
 * LIKELIHOOD_INVERSION_FILTER
 * SMOOTHER_INVERSION_FILTER
 * FILTER_USE_RELEXATION
 * LIKELIHOOD_PIECEWISE_KALMAN_FILTER
 * SMOOTHER_PIECEWISE_KALMAN_FILTER
 * LIKELIHOOD_MAX_KALMAN_ITERATIONS
 * TRUE
 * BIND
 * RELAX
 * ERROR_BIND
 * ERROR_RELAX
 * UNIFORM_PDF
 * UNIT_ROOT_VARS
 * USE_DLL
 * USEAUTOCORR
 * GSA_SAMPLE_FILE
 * USE_UNIVARIATE_FILTERS_IF_SINGULARITY_IS_DETECTED
 * VALUES
 * SCALES
 * VAR
 * VAREXO
 * VAREXO_DET
 * VARIABLE
 * VAROBS
 * VAREXOBS
 * PREDETERMINED_VARIABLES
 * VAR_EXPECTATION
 * VAR_EXPECTATION_MODEL
 * PLOT_SHOCK_DECOMPOSITION
 * MODEL_LOCAL_VARIABLE
 * WRITE_LATEX_DYNAMIC_MODEL
 * WRITE_LATEX_STATIC_MODEL
 * WRITE_LATEX_ORIGINAL_MODEL
 * WRITE_LATEX_STEADY_STATE_MODEL
 * XLS_SHEET
 * XLS_RANGE
 * LMMCP
 * BANDPASS_FILTER
 * COLORMAP
 * VAR_MODEL
 * PAC_MODEL
 * QOQ
 * YOY
 * AOA
 * PAC_EXPECTATION
 * TREND_COMPONENT_MODEL
