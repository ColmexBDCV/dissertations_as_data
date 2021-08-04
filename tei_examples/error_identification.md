# Most common mistake in year tag

## 0200 

[15 examples of this mistake](https://github.com/ColmexBDCV/dissertations_as_data/tree/main/tei_examples/0200_year_error)

#### Page numbers (pp.200) get tagged as year 
1. Original reference: Garza Mercado, Ario. _Función y forma de la biblioteca elementos de planeación y diseño de bibliotecas universitarias y públicas_. 3 ed. México D. F.: Porrúa, 2009. **200p.** | [Grobid result](https://github.com/ColmexBDCV/dissertations_as_data/blob/main/tei_examples/0200_year_error/2012-ruiz-ferraez-roberto.xml#L1542-L1553)
2. Original reference: Sehimi, Mustatfa, (2000): Citations de S.M Mohammed VI, Okad, Rabat, **200 pp.** | [Grobid result](https://raw.githubusercontent.com/ColmexBDCV/dissertations_as_data/main/tei_examples/0200_year_error/2012-sanchez-bernal-indira-iasel.xml)
3. Original reference: ----- (2006). Sistemas complejos. Conceptos, método y fundamentación epistemológica de la investigación interdisciplinaria, Barcelona, Gedisa, **200 pp**. ISBN 978-849-784-164-1 | [Grobid result](https://github.com/ColmexBDCV/dissertations_as_data/blob/main/tei_examples/0200_year_error/2013-gonzalez-gonzalez-edgar-leonel.xml#L2152-L2163)
4. Original reference: Flynn, Maureen, Sacred Charity. Confraternities and social welfare in Spain, 1400-1700, Nueva York, Cornell University, 1989, **200 p**. | [Grobid result](https://github.com/ColmexBDCV/dissertations_as_data/blob/main/tei_examples/0200_year_error/2014-hernandez-vazquez-victor-manuel.xml#L599-L617)


#### Archive's box number

1. Original reference: “Campamento 2 de octubre: Respuesta del Comité Central Ejecutivo al desplegado de Francisco de la Cruz de adhesión al PRI”, México D.F., 14 de octubre de 1978. Enah, México D.F., F. Religiones, S. Cencos, caja **200**, Comunicación Cencos no. 42-78, ff. 8-9. | [Grobid result](https://raw.githubusercontent.com/ColmexBDCV/dissertations_as_data/main/tei_examples/0200_year_error/2013-calvo-isaza-oscar-ivan.xml)
```xml
<biblStruct xml:id="b400">
	<analytic>
		<title level="a" type="main" xml:id="_PAf4GXK">Campamento 2 de octubre: Respuesta del Comité Central Ejecutivo al desplegado de Francisco de la Cruz de adhesión al PRI</title>
		<author>
			<persName xmlns="http://www.tei-c.org/ns/1.0"><forename type="first">México</forename><forename type="middle">D F</forename><surname>Enah</surname></persName>
		</author>
		<author>
			<persName xmlns="http://www.tei-c.org/ns/1.0"><forename type="first">F</forename><surname>Religiones</surname></persName>
		</author>
		<author>
			<persName xmlns="http://www.tei-c.org/ns/1.0"><forename type="first">S</forename><surname>Cencos</surname></persName>
		</author>
	</analytic>
	<monogr>
		<title level="m" xml:id="_WQKxmCf">Punto Crítico (México) oct</title>
		<meeting><address><addrLine>México D.F.</addrLine></address></meeting>
		<imprint>
			<date type="published" when="0200" />
			<biblScope unit="volume">14</biblScope>
			<biblScope unit="page" from="25" to="27" />
		</imprint>
	</monogr>
	<note>Campamento 2 de octubre &apos;Con Panchito hasta el infierno. Comunicación Cencos no. 42-78, ff. 8-9</note>
</biblStruct>
```

#### Journals' number

1. Original reference: Dilthey, Wilhelm, Crítica de la razón histórica, edición Hans-Ulrich Lessing, trad. y pról. Carlos Moya Espí, Barcelona, Península, 1986 (Historia, ciencia, sociedad, **200**). | [Grobid result](https://github.com/ColmexBDCV/dissertations_as_data/blob/main/tei_examples/0200_year_error/2013-gomez-mostajo-felix-roberto.xml#L1754-L1768)

#### A table that got parsed as a reference

1. Original reference:
![image](https://user-images.githubusercontent.com/8223258/128096702-ff2b8965-2701-4aca-a75e-6203deaf9957.png)
Grobids result:
```xml
<biblStruct xml:id="b8">
	<monogr>
		<title/>
		<author>
			<persName><forename type="first">Carbonífera</forename><surname>Unida De Palau</surname></persName>
		</author>
		<author>
			<persName><forename type="first">S</forename><forename type="middle">A</forename></persName>
		</author>
		<imprint>
			<date type="published" when="0200" />
			<biblScope unit="volume">35</biblScope>
			<biblScope unit="page">0</biblScope>
		</imprint>
	</monogr>
</biblStruct>
```
