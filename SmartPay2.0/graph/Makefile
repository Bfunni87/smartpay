#############################################################################
# Makefile for building: ../bin/graph
# Generated by qmake (2.01a) (Qt 4.7.2) on: Sat Feb 11 15:41:10 2012
# Project:  graph.pro
# Template: app
# Command: /usr/bin/qmake -o Makefile graph.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_NO_DEBUG -DQT_SQL_LIB -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtGui -I/usr/include/qt4/QtSql -I/usr/include/qt4 -I. -Itmp -Itmp
LINK          = g++
LFLAGS        = -Wl,-O1
LIBS          = $(SUBLIBS)  -L/usr/lib -lQtSql -lQtGui -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
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

OBJECTS_DIR   = tmp/

####### Files

SOURCES       = graph.cpp \
		graphwindow.cpp \
		main.cpp tmp/moc_graph.cpp \
		tmp/moc_graphwindow.cpp
OBJECTS       = tmp/graph.o \
		tmp/graphwindow.o \
		tmp/main.o \
		tmp/moc_graph.o \
		tmp/moc_graphwindow.o
DIST          = /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		../global.pri \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		graph.pro
QMAKE_TARGET  = graph
DESTDIR       = ../bin/
TARGET        = ../bin/graph

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

$(TARGET): tmp/ui_graphwindow.h $(OBJECTS)  
	@$(CHK_DIR_EXISTS) ../bin/ || $(MKDIR) ../bin/ 
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: graph.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		../global.pri \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/lib/libQtSql.prl \
		/usr/lib/libQtGui.prl \
		/usr/lib/libQtCore.prl
	$(QMAKE) -o Makefile graph.pro
/usr/share/qt4/mkspecs/common/g++.conf:
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
../global.pri:
/usr/share/qt4/mkspecs/features/release.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/lib/libQtSql.prl:
/usr/lib/libQtGui.prl:
/usr/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -o Makefile graph.pro

dist: 
	@$(CHK_DIR_EXISTS) tmp/graph1.0.0 || $(MKDIR) tmp/graph1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) tmp/graph1.0.0/ && $(COPY_FILE) --parents graph.h graphwindow.h tmp/graph1.0.0/ && $(COPY_FILE) --parents graph.cpp graphwindow.cpp main.cpp tmp/graph1.0.0/ && $(COPY_FILE) --parents graphwindow.ui tmp/graph1.0.0/ && (cd `dirname tmp/graph1.0.0` && $(TAR) graph1.0.0.tar graph1.0.0 && $(COMPRESS) graph1.0.0.tar) && $(MOVE) `dirname tmp/graph1.0.0`/graph1.0.0.tar.gz . && $(DEL_FILE) -r tmp/graph1.0.0


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

compiler_moc_header_make_all: tmp/moc_graph.cpp tmp/moc_graphwindow.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) tmp/moc_graph.cpp tmp/moc_graphwindow.cpp
tmp/moc_graph.cpp: graph.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) graph.h -o tmp/moc_graph.cpp

tmp/moc_graphwindow.cpp: tmp/ui_graphwindow.h \
		graphwindow.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) graphwindow.h -o tmp/moc_graphwindow.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: tmp/qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) tmp/qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: tmp/ui_graphwindow.h
compiler_uic_clean:
	-$(DEL_FILE) tmp/ui_graphwindow.h
tmp/ui_graphwindow.h: graphwindow.ui \
		graph.h
	/usr/bin/uic-qt4 graphwindow.ui -o tmp/ui_graphwindow.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_uic_clean 

####### Compile

tmp/graph.o: graph.cpp graph.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o tmp/graph.o graph.cpp

tmp/graphwindow.o: graphwindow.cpp graphwindow.h \
		tmp/ui_graphwindow.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o tmp/graphwindow.o graphwindow.cpp

tmp/main.o: main.cpp graph.h \
		graphwindow.h \
		tmp/ui_graphwindow.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o tmp/main.o main.cpp

tmp/moc_graph.o: tmp/moc_graph.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o tmp/moc_graph.o tmp/moc_graph.cpp

tmp/moc_graphwindow.o: tmp/moc_graphwindow.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o tmp/moc_graphwindow.o tmp/moc_graphwindow.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

