# goconf
读取配置文件信息
get conf or ini file infomation

##使用方法
	import "github.com/dangwy/goconf"
  
	//Get config info
	conf := cof.SetConfig("conf/conf.ini")
	cdnsp := conf.GetValue("cdn", "cdnsp")
	cdnsaddr := conf.GetValue("cdn", "cdnsaddr")
	fmt.Println(cdnsp)
	fmt.Println(cdnsaddr)
	
##conf文件实例
	[cdn]
	cdnsp=link
	cdnsaddr=rtsp://10.10.10.10:8099

##about
	有问题，请联系：dangwy@gmail.com
