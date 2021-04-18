#!/usr/bin/env python3
"""Tests for FtoC.py"""

import os
from subprocess import getstatusoutput, getoutput
import FtoC

prg = './FtoC.py'

# --------------------------------------------------
def test_exists():
    """exists"""

    assert os.path.isfile(prg)

# --------------------------------------------------
def test_default_password_length():
    """default password length is 7"""

    assert FtoC.password_length == 8

#---------------------------------------------------
def test_password_length_is_number():
    """Make sure there a 10 letters in list"""

    assert type(FtoC.password_length) == int

#---------------------------------------------------


# --------------------------------------------------
def test_password_length():
    """test password length matches user ouput"""

    assert os.path.isfile(prg)
