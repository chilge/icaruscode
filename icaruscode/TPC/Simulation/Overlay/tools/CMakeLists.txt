cet_enable_asserts()

art_make( 
          TOOL_LIBRARIES  larcorealg_Geometry
			              larevt_CalibrationDBI_IOVData
			              larevt_CalibrationDBI_Providers
			              larreco_HitFinder
			              lardataobj_RecoBase
			              larcore_Geometry_Geometry_service
			              lardata_Utilities
			              nurandom_RandomUtils_NuRandomService_service
                          ${ICARUS_FFTW_LIBRARIES}
  			              ${ART_FRAMEWORK_CORE}
			              ${ART_FRAMEWORK_PRINCIPAL}
			              ${ART_FRAMEWORK_SERVICES_REGISTRY}
			              art_Persistency_Common
			              art_Persistency_Provenance
			              ${ART_FRAMEWORK_SERVICES_BASIC}
			              ${ART_ROOT_IO_TFILE_SUPPORT} ${ROOT_CORE}
                          ${ART_FRAMEWORK_SERVICES_OPTIONAL_RANDOMNUMBERGENERATOR_SERVICE}
			              ${ART_ROOT_IO_TFILESERVICE_SERVICE}
			              ${ART_FRAMEWORK_SERVICES_SYSTEM_FILECATALOGMETADATA_SERVICE}
			              art_Utilities
			              canvas
			              ${MF_MESSAGELOGGER}
			              ${MF_UTILITIES}
			              ${FHICLCPP}
			              ${CETLIB}
			              ${Boost_FILESYSTEM_LIBRARY}
			              ${Boost_SYSTEM_LIBRARY}
                          ${CLHEP}
			              ${ROOT_BASIC_LIB_LIST}
    )

install_headers()
install_source()
install_fhicl()
