#############################################################################
# Makefile for building: qtInterface
# Generated by qmake (2.01a) (Qt 4.6.3) on: Wed Dec 19 15:00:36 2012
# Project:  qtInterface.pro
# Template: app
# Command: /home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/bin/qmake -unix -o Makefile qtInterface.pro
#############################################################################

####### Compiler, tools and options

CC            = $(OE_QMAKE_CC)
CXX           = $(OE_QMAKE_CXX)
DEFINES       = -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe $(OE_QMAKE_CFLAGS) -D_REENTRANT -Wall -W $(DEFINES)
CXXFLAGS      = -pipe $(OE_QMAKE_CFLAGS) $(OE_QMAKE_CXXFLAGS) -DPlatform_$(PLATFORM) -D_REENTRANT -Wall -W $(DEFINES)
INCPATH       = -I../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/linux-g++ -I. -I$(OE_QMAKE_INCDIR_QT)/QtCore -I$(OE_QMAKE_INCDIR_QT)/QtGui -I$(OE_QMAKE_INCDIR_QT) -I.
LINK          = $(OE_QMAKE_LINK)
LFLAGS        = $(OE_QMAKE_LDFLAGS)
LIBS          = $(SUBLIBS)  -L$(OE_QMAKE_LIBDIR_QT) -lQtGuiE -lQtNetworkE -lQtCoreE -lglib-2.0 -lpthread 
AR            = $(OE_QMAKE_AR) cqs
RANLIB        = 
QMAKE         = /home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = $(OE_QMAKE_STRIP)
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = messageserver.cpp \
		controlwindow.cpp \
		configwindow.cpp \
		main.cpp \
		osdmanager.cpp moc_messageserver.cpp \
		moc_configwindow.cpp \
		moc_controlwindow.cpp \
		moc_osdmanager.cpp \
		qrc_qtinterface.cpp
OBJECTS       = messageserver.o \
		controlwindow.o \
		configwindow.o \
		main.o \
		osdmanager.o \
		moc_messageserver.o \
		moc_configwindow.o \
		moc_controlwindow.o \
		moc_osdmanager.o \
		qrc_qtinterface.o
DIST          = ../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/g++.conf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/unix.conf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/linux.conf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/qconfig.pri \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt_functions.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt_config.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/exclusive_builds.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/default_pre.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/release.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/default_post.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/link_pkgconfig.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/unix/thread.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/warn_on.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/moc.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/resources.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/uic.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/yacc.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/lex.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/include_source_dir.prf \
		qtInterface.pro
QMAKE_TARGET  = qtInterface
DESTDIR       = 
TARGET        = qtInterface

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: qtInterface.pro  ../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/linux-g++/qmake.conf ../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/g++.conf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/unix.conf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/linux.conf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/qconfig.pri \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt_functions.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt_config.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/exclusive_builds.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/default_pre.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/release.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/default_post.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/link_pkgconfig.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/unix/thread.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/warn_on.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/moc.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/resources.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/uic.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/yacc.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/lex.prf \
		../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/include_source_dir.prf \
		/home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/arm-none-linux-gnueabi/usr/lib/libQtGuiE.prl \
		/home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/arm-none-linux-gnueabi/usr/lib/libQtNetworkE.prl \
		/home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/arm-none-linux-gnueabi/usr/lib/libQtCoreE.prl
	$(QMAKE) -unix -o Makefile qtInterface.pro
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/g++.conf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/unix.conf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/common/linux.conf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/qconfig.pri:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt_functions.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt_config.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/exclusive_builds.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/default_pre.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/release.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/default_post.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/link_pkgconfig.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/unix/thread.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/warn_on.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/qt.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/moc.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/resources.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/uic.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/yacc.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/lex.prf:
../../linux-devkit/arm-none-linux-gnueabi/usr/share/qtopia/mkspecs/features/include_source_dir.prf:
/home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/arm-none-linux-gnueabi/usr/lib/libQtGuiE.prl:
/home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/arm-none-linux-gnueabi/usr/lib/libQtNetworkE.prl:
/home/amironenko/ti-dvsdk_dm365-evm_4_02_00_06/linux-devkit/arm-none-linux-gnueabi/usr/lib/libQtCoreE.prl:
qmake:  FORCE
	@$(QMAKE) -unix -o Makefile qtInterface.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/qtInterface1.0.0 || $(MKDIR) .tmp/qtInterface1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/qtInterface1.0.0/ && $(COPY_FILE) --parents messageserver.h configwindow.h controlwindow.h osdmanager.h qtinterface.h .tmp/qtInterface1.0.0/ && $(COPY_FILE) --parents qtinterface.qrc .tmp/qtInterface1.0.0/ && $(COPY_FILE) --parents messageserver.cpp controlwindow.cpp configwindow.cpp main.cpp osdmanager.cpp .tmp/qtInterface1.0.0/ && (cd `dirname .tmp/qtInterface1.0.0` && $(TAR) qtInterface1.0.0.tar qtInterface1.0.0 && $(COMPRESS) qtInterface1.0.0.tar) && $(MOVE) `dirname .tmp/qtInterface1.0.0`/qtInterface1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/qtInterface1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_messageserver.cpp moc_configwindow.cpp moc_controlwindow.cpp moc_osdmanager.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_messageserver.cpp moc_configwindow.cpp moc_controlwindow.cpp moc_osdmanager.cpp
moc_messageserver.cpp: qtinterface.h \
		messageserver.h
	$(OE_QMAKE_MOC) $(DEFINES) $(INCPATH) messageserver.h -o moc_messageserver.cpp

moc_configwindow.cpp: messageserver.h \
		qtinterface.h \
		controlwindow.h \
		osdmanager.h \
		configwindow.h
	$(OE_QMAKE_MOC) $(DEFINES) $(INCPATH) configwindow.h -o moc_configwindow.cpp

moc_controlwindow.cpp: messageserver.h \
		qtinterface.h \
		osdmanager.h \
		controlwindow.h
	$(OE_QMAKE_MOC) $(DEFINES) $(INCPATH) controlwindow.h -o moc_controlwindow.cpp

moc_osdmanager.cpp: osdmanager.h
	$(OE_QMAKE_MOC) $(DEFINES) $(INCPATH) osdmanager.h -o moc_osdmanager.cpp

compiler_rcc_make_all: qrc_qtinterface.cpp
compiler_rcc_clean:
	-$(DEL_FILE) qrc_qtinterface.cpp
qrc_qtinterface.cpp: qtinterface.qrc \
		images/hdr_ti_logo.png
	$(OE_QMAKE_RCC) -name qtinterface qtinterface.qrc -o qrc_qtinterface.cpp

compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_rcc_clean 

####### Compile

messageserver.o: messageserver.cpp messageserver.h \
		qtinterface.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o messageserver.o messageserver.cpp

controlwindow.o: controlwindow.cpp qtinterface.h \
		controlwindow.h \
		messageserver.h \
		osdmanager.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o controlwindow.o controlwindow.cpp

configwindow.o: configwindow.cpp configwindow.h \
		messageserver.h \
		qtinterface.h \
		controlwindow.h \
		osdmanager.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o configwindow.o configwindow.cpp

main.o: main.cpp qtinterface.h \
		configwindow.h \
		messageserver.h \
		controlwindow.h \
		osdmanager.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

osdmanager.o: osdmanager.cpp osdmanager.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o osdmanager.o osdmanager.cpp

moc_messageserver.o: moc_messageserver.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_messageserver.o moc_messageserver.cpp

moc_configwindow.o: moc_configwindow.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_configwindow.o moc_configwindow.cpp

moc_controlwindow.o: moc_controlwindow.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_controlwindow.o moc_controlwindow.cpp

moc_osdmanager.o: moc_osdmanager.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_osdmanager.o moc_osdmanager.cpp

qrc_qtinterface.o: qrc_qtinterface.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o qrc_qtinterface.o qrc_qtinterface.cpp

####### Install

install_target: first FORCE
	@$(CHK_DIR_EXISTS) $(INSTALL_ROOT)/$(EXEC_DIR)/ || $(MKDIR) $(INSTALL_ROOT)/$(EXEC_DIR)/ 
	-$(INSTALL_PROGRAM) "$(QMAKE_TARGET)" "$(INSTALL_ROOT)/$(EXEC_DIR)/$(QMAKE_TARGET)"
	-$(STRIP) "$(INSTALL_ROOT)/$(EXEC_DIR)/$(QMAKE_TARGET)"

uninstall_target:  FORCE
	-$(DEL_FILE) "$(INSTALL_ROOT)/$(EXEC_DIR)/$(QMAKE_TARGET)"
	-$(DEL_DIR) $(INSTALL_ROOT)/$(EXEC_DIR)/ 


install:  install_target  FORCE

uninstall: uninstall_target   FORCE

FORCE:

