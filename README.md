���ۑ�������e  
key					value(�^)							meaning  
title					string								�T�C�g�̃^�C�g��  
URL					string								�T�C�gURL  
created_at		timestamp						�o�^����  
deleted_at		timestamp						�폜�\�����  
state				int									�Ƃ肠�����A������ƋC�ɂȂ�A�����ۑ�  
comment			string								�R�����g  


��favicon�摜�̎擾��Google API�Łi�Q�l�j  
http://9ensan.com/blog/webservice/favicon-google-api/  
http://favicon.qfor.info/f/  


�����g���₷��  
�X���C�v�ō폜	OK  
�T���l�摜API	OK  
 �ior �X�N���C�s���O�ŉ摜�B���Ă���Ȃ��H�j  
���Ԍo�߂ō폜	OK  
State�ɂ���č폜���邩���߂�  


��24���Ԍo�ߌ�  
Done�̂��́F�A�[�J�C�u�Ɉړ�  
	Archive Collection has Todo model  
	�A�[�J�C�u����͌����폜���Ȃ�  
	Twitter���ۂ����[�h�ł��Ȃ����H  
		pager:  
			model��page�@attributes��ǉ�����B  
			collection.create()����ۂɁAcollection.length������Ă���B  
			�����perPage(1�y�[�W������̋L����)�Ŋ���B����؂�̂Ă�����+1����΁A���ꂪ�y�[�W���ƂȂ�B  
			ex) perPage = 50, collection.length = 120, -> page: 3  
			http://mixmaru.com/?p=274  
NotDone�̂��́F���S�폜  