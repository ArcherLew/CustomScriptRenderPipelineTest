# CustomScriptRenderPipelineTest
## About
���̃v���W�F�N�g�� ���삵��ScriptableRenderPipeline(SRP)�̃e�X�g�p�ɍ쐬���܂����B<br />
���̃v���W�F�N�g��p�� Shader / �`��p�X�ɓ��������`�ł���Ă��܂��B<br />

## SRP�g�p�̃I���^�I�t��؂�ւ��Ă݂�
Menu�́uTools/SRPChanger�v�̃`�F�b�N�{�b�N�X�� On/Off��؂�ւ��邱�ƂŁA�ʏ�̕`��p�X�ƍ���̐�p�`��p�X��؂�ւ����܂��B<br />
![alt text](doc/SPRChanger.png)

���g�p���� Batches 3733

![alt text](doc/SRPOff.png)

�����p��Rendering�p�X���� Batches 31

![alt text](doc/CustomSRPOn.png)

��p�ɗp�ӂ��邱�ƂŐ����y�����邱�Ƃ��o���܂����B

## ���邭���
### �ʏ�̃p�X
�ʏ�ł́ATransparent�͕`��̔j�]��h�����߁u�������O�v�ɕ`������܂��B<br />
�����_�����O�̔j�]��h�����߁A���L�̗l�Ɂu�������O�v�����炵�܂��B<br/>
���̂��߁A�u�e���L�����N�^�[���e�v�Ƃ����`�Ń}�e���A�����R�؂�ւ��Ȃ���`������܂��̂ŁA�o�b�`���͖c��݂܂��B<br />

![alt text](doc/SRPOff_FrameDebugger.png)

### ����J�X�^���̕`��p�X
����́A���L�菇�ŏ�������ł��܂��B

1.��ɃL�����N�^�[�̃���0�o�Ȃ��ӏ��̂݁AZBuffer�֏�������<br />
2.����ǂ̕`��<br />
3.�L�����N�^�[�̎��̂�ZTest�ň�v�������̂ݕ`�悷��悤�ɂ���<br />
4.�Ō�ɉe��[�x�e�X�g����ň�C�ɏ�������<br />

���̂悤�ɂ��邱�ƂŁA�}�e���A���؂�ւ���}���`�悷��悤�ɂ��Ă��܂��B<br />

FrameDebugger�ŉ��L�̗l�ɂȂ��Ă��܂��B

![alt text](doc/CustomFrame1.png)

![alt text](doc/CustomFrame2.png)

![alt text](doc/CustomFrame3.png)


## �\�[�X��

MyScriptableRenderPipeline.cs �ɂă����_�����O�֘A�̏������s���Ă��܂��B<br />
ScriptableRenderPiepeline�g�p���ɂ́A�uTags { "LightMode" = "BasicPass"}�v�ƌ����`�ŕ`��p�̃p�X�^�O��錾����K�v������܂��B<br />

���̂��߁A�����SRP�g�p�̂��߂̐�pShader�������܂����B<br />
�uAssets/Shaders/SRP�v�����炪 SRP�g�p���ɗ��p���� Shader<br />
<br />
�ʏ펞�ɂ́A�uAssets/Shaders/NonSRP�v�𗘗p���ĕ`�悵�Ă��܂��B
