react-drop용 파일포맷 템플릿

```javascript
const fileUploaderState = useFileUploader({
    onDrop: (acceptedFiles) => {
      setFiles(acceptedFiles);
    },
    accept: {
      'application/vnd.ms-excel': ['.xls', '.slk', '.xla', '.xlt', '.xlw'],
      'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet': [
        '.xlsx',
      ],
      'text/csv': ['.csv'],
      'text/html': ['.htm', '.html'],
      'text/plain': ['.txt', '.dif'],
      'application/x-iwork-numbers-sffnumbers': ['.numbers'],
      'text/xml': ['.xml'],
      'application/vnd.oasis.opendocument.spreadsheet': ['.ods'],
      'application/vnd.oasis.opendocument.text': ['.odt'],
      'application/octet-stream': [],
      'video/x-dv': [],
      'multipart/related': ['.mhtl'],
      'application/vnd.ms-excel.sheet.binary.macroenabled.12': ['.xlsb'],
      'application/vnd.ms-excel.sheet.macroenabled.12': ['.xlsm'],
      'application/vnd.ms-excel.template.macroenabled.12': ['.xltm'],
      'application/vnd.ms-excel.addin.macroenabled.12': ['.xlam'],
      'application/x-dbase': ['.dbf'],
      'message/rfc822': ['.mht'],
    },
  });
```