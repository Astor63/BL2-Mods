Entre la skin de la Moxxi et celle de la Commerce, j'ai remarqué ces -grandes?- différences dans le code:

- Skin Moxxi (2 Lignes de code)
 ```
(ParameterName="p_ReplacePattern",ParameterValue=1.000000,ExpressionGUID=(A=-2084339847,B=1096440125,C=439008937,D=45433490))
(ParameterName="P_SimpleReflect",ParameterValue=Texture2D'Common_GunMaterials.Env.GlossyC',ExpressionGUID=(A=-858148940,B=1327945772,C=148462268,D=1899047224)),
 ```
- Skin Commerce (2 lignes de codes)
```
(ParameterName="p_ReplacePattern",ParameterValue=0.000000,ExpressionGUID=(A=-2084339847,B=1096440125,C=439008937,D=45433490))
(ParameterName="P_SimpleReflect",ParameterValue=Texture2D'Common_GunMaterials.Patterns.Pattern_Lightning',ExpressionGUID=(A=-858148940,B=1327945772,C=148462268,D=1899047224))
```
 Et 3 lignes en plus (qui ne sont pas écrasées par le fichier de la HeartBreaker)
```
ScalarParameterValues(4)=(ParameterName="p_UseFullColorDecal",ParameterValue=0.000000,ExpressionGUID=(A=-1064329812,B=1077705328,C=339664807,D=1869745420))
VectorParameterValues(10)=(ParameterName="p_ReflectionChannelScale",ParameterValue=(R=1.000000,G=0.400000,B=0.000000,A=1.000000),ExpressionGUID=(A=1869386622,B=1303200947,C=-1616405849,D=714558284))
VectorParameterValues(12)=(ParameterName="p_DecalColor",ParameterValue=(R=1.730582,G=3.275289,B=6.960011,A=1.000000),ExpressionGUID=(A=1691998600,B=1239094551,C=2074257317,D=1844701893))
```
