project(org_gdmc_segmentation_regiongrowing)

MACRO_CREATE_MITK_CTK_PLUGIN(
  EXPORT_DIRECTIVE REGIONGROWING_EXPORT
  EXPORTED_INCLUDE_SUFFIXES src
  MODULE_DEPENDENCIES QmitkExt
)
