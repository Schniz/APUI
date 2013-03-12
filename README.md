APUI
====

Functional programming via GUI.

awesome.

XML Example
-----------
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Flow>
  <Command name="Condition">
		<Attributes>
			<Attribute name="condition">
				<And>
					<Evaluator name="myEvaluator" operator="is" />
				</And>
			</Attribute>
		</Attribute>
		<IsTrue>
			<Command name="Yossi">
				<Attributes>
					<Attribute name="Bla">Value</Attribute>
				</Attributes>
			</Command>
		</IsTrue>
		<IsFalse>
			<Command name="Yossi">
				<Attributes>
					<Attribute name="Bla">Value</Attribute>
				</Attributes>
			</Command>
		</IsFalse>
	</Command>
</Flow>
```
