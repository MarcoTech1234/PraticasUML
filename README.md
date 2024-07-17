# PraticasUML
Pasta para armazenar diagramas de uml feitas durante o aprendizado

<mxfile host="app.diagrams.net" modified="2024-07-17T23:57:54.349Z" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/126.0.0.0 Safari/537.36" etag="5tcn1eduzCE1HZJJKc9R" version="24.7.1" type="github">
  <diagram id="C5RBs43oDa-KdzZeNtuy" name="Page-1">
    <mxGraphModel dx="1518" dy="614" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="WIyWlLk6GJQsqaUBKTNV-0" />
        <mxCell id="WIyWlLk6GJQsqaUBKTNV-1" parent="WIyWlLk6GJQsqaUBKTNV-0" />
        <mxCell id="pdAf4XXUezwkvFrkvtL9-1" value="&lt;div style=&quot;&quot;&gt;&lt;span style=&quot;background-color: initial;&quot;&gt;&amp;lt;&amp;lt;interface&amp;gt;&amp;gt;&lt;/span&gt;&lt;/div&gt;&lt;div style=&quot;&quot;&gt;&lt;span style=&quot;font-weight: 400;&quot;&gt;AparelhoTelefonico&lt;/span&gt;&lt;/div&gt;" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=40;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="3" y="156" width="200" height="104" as="geometry">
            <mxRectangle x="290" y="140" width="110" height="40" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-2" value="+ ligar (numero: String): void&lt;div&gt;+ atender (): void&lt;br&gt;+ iniciarCorreioVoz(): void&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="pdAf4XXUezwkvFrkvtL9-1">
          <mxGeometry y="40" width="200" height="64" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-5" value="&amp;lt;&amp;lt;interface&amp;gt;&amp;gt;&lt;br&gt;&lt;span style=&quot;font-weight: 400;&quot;&gt;ReprodutorMusical&lt;/span&gt;" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=40;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="550" y="153" width="240" height="110" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-6" value="+ tocar ():void&lt;br&gt;+ pausar (): void&lt;br&gt;+ selecionarMusica(musica: String): void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="pdAf4XXUezwkvFrkvtL9-5">
          <mxGeometry y="40" width="240" height="70" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-10" value="&amp;lt;&amp;lt;interface&amp;gt;&amp;gt;&lt;br&gt;&lt;span style=&quot;font-weight: normal;&quot;&gt;NavegadorInterrnet&lt;/span&gt;" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=40;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="270" y="156" width="210" height="100" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-11" value="+ exibirPagina (url: String): void&lt;br&gt;+ adicionarNovaAba (): void&lt;br&gt;+ atualizarPagina (): void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="pdAf4XXUezwkvFrkvtL9-10">
          <mxGeometry y="40" width="210" height="60" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="WIyWlLk6GJQsqaUBKTNV-1" source="pdAf4XXUezwkvFrkvtL9-14">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="390" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.25;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="WIyWlLk6GJQsqaUBKTNV-1" source="pdAf4XXUezwkvFrkvtL9-14">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="160" y="270" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-14" value="Iphone" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="320" y="510" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-23" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="WIyWlLk6GJQsqaUBKTNV-1" source="pdAf4XXUezwkvFrkvtL9-18">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="679.6470588235293" y="270" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-18" value="Chrome" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="660" y="440" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="WIyWlLk6GJQsqaUBKTNV-1" source="pdAf4XXUezwkvFrkvtL9-19">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="119.6470588235295" y="270" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-19" value="Ipod" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="50" y="440" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-22" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="WIyWlLk6GJQsqaUBKTNV-1" source="pdAf4XXUezwkvFrkvtL9-20">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="440" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-20" value="Nokia" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="WIyWlLk6GJQsqaUBKTNV-1">
          <mxGeometry x="490" y="440" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="pdAf4XXUezwkvFrkvtL9-25" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.75;exitY=0;exitDx=0;exitDy=0;entryX=0.215;entryY=1.083;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="WIyWlLk6GJQsqaUBKTNV-1" source="pdAf4XXUezwkvFrkvtL9-14" target="pdAf4XXUezwkvFrkvtL9-6">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="425" y="370" />
              <mxPoint x="600" y="370" />
              <mxPoint x="600" y="270" />
              <mxPoint x="602" y="270" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
