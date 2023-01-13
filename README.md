# ProgLangLab2
## Get files list
    http://localhost:5000/myFiles?path=${path}
    where path - way to folder
    result
    {
		data: 
			files:[{allFiles}]
		status: 200
	}
## Download file
    http://localhost:5000/downloadFile?path=${path}
    where path - way to folder    