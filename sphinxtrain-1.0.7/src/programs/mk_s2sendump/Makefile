# ====================================================================
# Copyright (c) 2000 Carnegie Mellon University.  All rights reserved.
#
# Redistribution and use in source and binary forms, with or without
# modification, are permitted provided that the following conditions
# are met:
#
# 1. Redistributions of source code must retain the above copyright
#    notice, this list of conditions and the following disclaimer. 
#
# 2. Redistributions in binary form must reproduce the above copyright
#    notice, this list of conditions and the following disclaimer in
#    the documentation and/or other materials provided with the
#    distribution.
#
# 3. The names "Sphinx" and "Carnegie Mellon" must not be used to
#    endorse or promote products derived from this software without
#    prior written permission. To obtain permission, contact 
#    sphinx@cs.cmu.edu.
#
# 54 Redistributions of any form whatsoever must retain the following
#    acknowledgment:
#    "This product includes software developed by Carnegie
#    Mellon University (http://www.speech.cs.cmu.edu/)."
#
# THIS SOFTWARE IS PROVIDED BY CARNEGIE MELLON UNIVERSITY ``AS IS'' AND 
# ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, 
# THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
# PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL CARNEGIE MELLON UNIVERSITY
# NOR ITS EMPLOYEES BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
# SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT 
# LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, 
# DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY 
# THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT 
# (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE 
# OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
#
# ====================================================================
#
#  Programs: mk_s2sendump
#
#  Sucked in stuff from s3 so SphinxTrain can be standalone but 
#  this make sthis function very bad as it has random stuff from 
#  libraries that should be those libraries not here.
#
# ====================================================================
TOP=../../..
DIRNAME=src/programs/mk_s2sendump
BUILD_DIRS = 
ALL_DIRS= $(BUILD_DIRS)
SRCS = \
  mk_s2sendump.c \
  senone.c       \
  parse_cmd_ln.c

H = \
  senone.h \
  parse_cmd_ln.h

FILES = Makefile $(SRCS) $(H)

TARGET = mk_s2sendump

ALL = $(BINDIR)/$(TARGET)

include $(TOP)/config/common_make_rules

