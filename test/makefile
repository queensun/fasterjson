# 此文件由makeobj.sh自动生成
############################################################
# 项目名 : 
# 模块名 : 
# 备  注 : 
############################################################

###### 源文件配置区
#@ c_FILE
c_FILE		=	\
			test_fasterjson.c \
			press_fasterjson.c \

###### 目标文件、安装目录配置区
BIN		=	test_fasterjson \
			press_fasterjson \

###### 编译选项
CFLAGS		=	-I. \
			-I$(HOME)/include/fasterjson \

###### 链接选项
LFLAGS		=	-L. \
			-L$(HOME)/lib \
			-lfasterjson \

###### 额外宏定义区
CLEAN_ADDITION	=

###### 加载mktpl模板库
#@ make_all
#@ make_clean
#@ make_install
#@ make_install_BININST
#@ make_install_DFTHDERINST

include $(MKTPLDIR)/makeobj_$(MKTPLOS).inc

###### 目标文件依赖关系
test_fasterjson		:	test_fasterjson.o
	$(CC) -o $@ test_fasterjson.o $(LFLAGS)

press_fasterjson		:	press_fasterjson.o
	$(CC) -o $@ press_fasterjson.o $(LFLAGS)

