==========================
 XPS
==========================

XPS�̃f�[�^�ϊ��菇
===================

1�DXPS���f�[�^�isurvey1�{�̂�OK�j:MIDATA001.104.spe

2�DPHI�쐬�ϊ��c�[��:MPExport.exe

3�D#1��#2�ŕϊ������e�L�X�g�f�[�^: MIDATA001.104.txt

4�D#3����CFND�����c�[��: txttocsvforphi.py

5�D#3����#4�ŕϊ�����FND�t�@�C��: MIDATA001.104.csv

6�DFND�t�@�C������X�y�N�g���̐}���쐬����c�[��: csvtograph.py

7�D#5����#6�ō쐬����PNG�t�@�C��: MIDATA001.104.png

�R�}���h
========

.spe�`���̃t�@�C�����e�L�X�g�t�@�C���ɕϊ����܂�::

	MPExpoter.exe -Filename:MIDATA001.104.spe -TSV

�e�L�X�g�t�@�C�����t�H�[�}�b�g���ꂽ���l�f�[�^(csv)�ɕϊ����܂�::

	python txttocsvforphi.py MIDATA001.104.txt

csv�t�@�C������摜���쐬���܂�::

	python csvtograph.py MIDATA001.104.csv

For more information, refer to the `the documentation`__.

.. __: https://github.com/nims-dpfc/Materials_Data_Repository/

Instrallation
=============

�����ɃC���X�g�[���̎菇������܂��B

Documentation
=============

�����Ƀh�L�������g���͂���܂��B