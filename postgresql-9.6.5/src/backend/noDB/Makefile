#-------------------------------------------------------------------------
#
# Makefile--
#    Makefile for rewrite
#
# IDENTIFICATION
#    $PostgreSQL: pgsql/src/backend/rewrite/Makefile,v 1.19 2009/01/27 12:40:15 petere Exp $
#
#-------------------------------------------------------------------------

subdir = src/backend/noDB
top_builddir = ../../..
include $(top_builddir)/src/Makefile.global

#OBJS = NoDBCache.o NoDBScanStrategy.o NoDBExecutor.o NoDBExecutorWithTimer.o NoDBScan.o NoDBEOLCacheWorld.o NoDBExecInfo.o 
OBJS = NoDBCache.o NoDBScanStrategy.o NoDBExecutor.o NoDBScan.o NoDBEOLCacheWorld.o NoDBExecInfo.o 

SUBDIRS = auxiliary 

include $(top_srcdir)/src/backend/common.mk
