<mxfile host="app.diagrams.net" modified="2026-03-31T20:20:00.000Z" agent="ClickUp Brain" version="24.7.8">
  <diagram id="patakeja-simple" name="PataKeja Simple Architecture">
    <mxGraphModel dx="1200" dy="800" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1400" pageHeight="900" math="0" shadow="0">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- Title -->
        <mxCell id="title" value="PataKeja Simple Architecture" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontSize=28;fontStyle=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="40" width="760" height="50" as="geometry"/>
        </mxCell>

        <!-- 6 Boxes -->
        <mxCell id="users" value="Users&#xa;(Students, Landlords, Admin)" style="rounded=1;whiteSpace=wrap;html=1;strokeColor=#6C8EBF;fillColor=#DAE8FC;align=center;verticalAlign=middle;fontSize=14;" vertex="1" parent="1">
          <mxGeometry x="80" y="260" width="190" height="120" as="geometry"/>
        </mxCell>

        <mxCell id="browser" value="Web Browser" style="rounded=1;whiteSpace=wrap;html=1;strokeColor=#6C8EBF;fillColor=#DAE8FC;align=center;verticalAlign=middle;fontSize=14;" vertex="1" parent="1">
          <mxGeometry x="300" y="260" width="190" height="120" as="geometry"/>
        </mxCell>

        <mxCell id="webserver" value="Web Server&#xa;(Nginx/Apache)" style="rounded=1;whiteSpace=wrap;html=1;strokeColor=#999999;fillColor=#F5F5F5;align=center;verticalAlign=middle;fontSize=14;" vertex="1" parent="1">
          <mxGeometry x="520" y="260" width="190" height="120" as="geometry"/>
        </mxCell>

        <mxCell id="laravel" value="Laravel App" style="rounded=1;whiteSpace=wrap;html=1;strokeColor=#6C8EBF;fillColor=#DAE8FC;align=center;verticalAlign=middle;fontSize=14;" vertex="1" parent="1">
          <mxGeometry x="740" y="260" width="190" height="120" as="geometry"/>
        </mxCell>

        <mxCell id="mysql" value="MySQL Database" style="rounded=1;whiteSpace=wrap;html=1;strokeColor=#82B366;fillColor=#D5E8D4;align=center;verticalAlign=middle;fontSize=14;" vertex="1" parent="1">
          <mxGeometry x="960" y="260" width="190" height="120" as="geometry"/>
        </mxCell>

        <mxCell id="storage" value="File Storage&#xa;(S3/Local)" style="rounded=1;whiteSpace=wrap;html=1;strokeColor=#999999;fillColor=#FFFFFF;align=center;verticalAlign=middle;fontSize=14;" vertex="1" parent="1">
          <mxGeometry x="1180" y="260" width="190" height="120" as="geometry"/>
        </mxCell>

        <!-- Arrows: Users→Browser→Web Server→Laravel→MySQL→Storage -->
        <mxCell id="e1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=block;endFill=1;strokeColor=#333333;" edge="1" parent="1" source="users" target="browser">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="e2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=block;endFill=1;strokeColor=#333333;" edge="1" parent="1" source="browser" target="webserver">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="e3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=block;endFill=1;strokeColor=#333333;" edge="1" parent="1" source="webserver" target="laravel">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="e4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=block;endFill=1;strokeColor=#333333;" edge="1" parent="1" source="laravel" target="mysql">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="e5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=block;endFill=1;strokeColor=#333333;" edge="1" parent="1" source="mysql" target="storage">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
