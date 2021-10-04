
# W2 Platform Changelog
All service affecting changes to the W2 platform or products will be documented in this page.

[W2 Home](https://www.w2globaldata.com)  
[W2 Portal](https://portal.w2globaldata.com)  
[W2 Dev Hub](https://www.w2globaldata.com/developers/)  

      


## Unreleased
### Bugs
- 22706 - Some addresses not showing correctly when searching for a postcode via Address Lookup.
- 23034 - KYC_Profiledata gives no data for PEPs and Sanctions when inputting sandbox data.

### Additions
- 22730 - Add a method to change the Risk Group of a case via the Case view.
- 22733 - Add UX elements for Case Management audit history 'download' button on the Case view.
- 22734 - Add ability to select date range for Case Management audit history downloads.
- 23082 - Add supplier integration for new KYC Germany and Netherlands feeds.
- 23133 - Add Liveness check to the Document Verification & Facial Comparison web journey.
- 23201 - Add IncludeExPEPsFromDate filter to the API.
- 23364 - Add the Risk Group information to the Case view on the Portal.

## 2021-10-01
### Fixed :zap:
- 23319 - Fixing an issue where the W2_DATA_EKYC_UK_015 service incorrectly returns unsuccessful results as 'None' instead of 'Not Performed'.
- 23363 - Document Upload Billing - Check additional image upload uses the correct billing tags.

## 2021-09-24
### Fixed :zap:
- 23452 - Fixed an issue with some documents showing a 503 timeout error in the Portal.
  
## 2021-09-23
### Added
- 23487 - Updated the Dev Docs page fo our SSN service with correct sandbox data. (https://docs.w2globaldata.com/#sandbox-33).
- 22736 - Added Generation of CSV report for Case Management audit history via the Portal.
  
## 2021-09-10
### Added
- 23504 - Service level interpretations for the SSN service, so it can be included as part of a Workflow (bundle).
- 22967 - Matching Engine distance matching updated to tolerate space and special characters in the middle of names.
