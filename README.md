<mxfile host="app.diagrams.net" modified="2025-06-18T00:00:00.000Z" agent="Mozilla/5.0" etag="er-diagram" version="21.0.0" type="device">
  <diagram name="ER-диаграмма" id="er-diagram">
    <mxGraphModel dx="1422" dy="794" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1600" pageHeight="1200" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />

        <!-- ========================================== -->
        <!-- Таблица: Заказчики -->
        <!-- ========================================== -->
        <mxCell id="2" value="Заказчики" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="40" y="40" width="240" height="240" as="geometry" />
        </mxCell>
        <mxCell id="3" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="4" value="PK ID_Заказчика" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="3">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="5" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="6" value="Наименование" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="5">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="7" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="8" value="ИНН" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="7">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="9" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="10" value="Адрес" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="9">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="11" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="150" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="12" value="Телефон" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="11">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="13" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="180" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="14" value="Флаг_Продавец" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="13">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="15" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="2">
          <mxGeometry y="210" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="16" value="Флаг_Покупатель" style="shape=partialRectangle;connectable=0;fillColor=#dae8fc;strokeColor=#6c8ebf;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="15">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Заказы -->
        <!-- ========================================== -->
        <mxCell id="17" value="Заказы" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="1">
          <mxGeometry x="40" y="360" width="240" height="210" as="geometry" />
        </mxCell>
        <mxCell id="18" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="17">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="19" value="PK ID_Заказа" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="18">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="20" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="17">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="21" value="FK ID_Заказчика" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="20">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="22" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="17">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="23" value="Номер_документа" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="22">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="24" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="17">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="25" value="Дата_заказа" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="24">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="26" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="17">
          <mxGeometry y="150" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="27" value="Исполнитель" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="26">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="28" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="17">
          <mxGeometry y="180" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="29" value="Сумма_итого" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="28">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Состав_Заказа -->
        <!-- ========================================== -->
        <mxCell id="30" value="Состав_Заказа" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="1">
          <mxGeometry x="420" y="360" width="240" height="240" as="geometry" />
        </mxCell>
        <mxCell id="31" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="32" value="PK ID_Строки" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="31">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="33" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="34" value="FK ID_Заказа" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="33">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="35" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="36" value="FK ID_Продукции" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="35">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="37" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="38" value="Количество" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="37">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="39" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="150" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="40" value="Цена" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="39">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="41" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="180" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="42" value="Сумма" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="41">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="43" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#ffe6cc;strokeColor=#d79b00;" vertex="1" parent="30">
          <mxGeometry y="210" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="44" value="Ед_изм" style="shape=partialRectangle;connectable=0;fillColor=#ffe6cc;strokeColor=#d79b00;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="43">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Продукция -->
        <!-- ========================================== -->
        <mxCell id="45" value="Продукция" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="1">
          <mxGeometry x="420" y="40" width="240" height="210" as="geometry" />
        </mxCell>
        <mxCell id="46" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="45">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="47" value="PK ID_Продукции" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="46">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="48" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="45">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="49" value="Наименование" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="48">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="50" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="45">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="51" value="Ед_изм" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="50">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="52" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="45">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="53" value="Цена" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="52">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="54" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="45">
          <mxGeometry y="150" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="55" value="Код_товара" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="54">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="56" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="45">
          <mxGeometry y="180" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="57" value="Размер" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="56">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Материалы -->
        <!-- ========================================== -->
        <mxCell id="58" value="Материалы" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="1">
          <mxGeometry x="820" y="40" width="240" height="180" as="geometry" />
        </mxCell>
        <mxCell id="59" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="58">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="60" value="PK ID_Материала" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="59">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="61" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="58">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="62" value="Наименование" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="61">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="63" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="58">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="64" value="Ед_изм" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="63">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="65" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="58">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="66" value="Цена" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="65">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="67" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="58">
          <mxGeometry y="150" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="68" value="Код_материала" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="67">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Спецификация_Продукции -->
        <!-- ========================================== -->
        <mxCell id="69" value="Спецификация_Продукции" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="1">
          <mxGeometry x="820" y="280" width="240" height="150" as="geometry" />
        </mxCell>
        <mxCell id="70" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="69">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="71" value="PK FK ID_Продукции" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="70">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="72" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="69">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="73" value="PK FK ID_Материала" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="72">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="74" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="69">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="75" value="Количество" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="74">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="76" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#d5e8d4;strokeColor=#82b366;" vertex="1" parent="69">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="77" value="Ед_изм" style="shape=partialRectangle;connectable=0;fillColor=#d5e8d4;strokeColor=#82b366;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="76">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Производство -->
        <!-- ========================================== -->
        <mxCell id="78" value="Производство" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#fff2cc;strokeColor=#d6b656;" vertex="1" parent="1">
          <mxGeometry x="40" y="650" width="240" height="150" as="geometry" />
        </mxCell>
        <mxCell id="79" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#fff2cc;strokeColor=#d6b656;" vertex="1" parent="78">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="80" value="PK ID_Производства" style="shape=partialRectangle;connectable=0;fillColor=#fff2cc;strokeColor=#d6b656;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="79">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="81" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#fff2cc;strokeColor=#d6b656;" vertex="1" parent="78">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="82" value="Номер" style="shape=partialRectangle;connectable=0;fillColor=#fff2cc;strokeColor=#d6b656;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="81">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="83" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#fff2cc;strokeColor=#d6b656;" vertex="1" parent="78">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="84" value="Дата_производства" style="shape=partialRectangle;connectable=0;fillColor=#fff2cc;strokeColor=#d6b656;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="83">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="85" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#fff2cc;strokeColor=#d6b656;" vertex="1" parent="78">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="86" value="Ответственный" style="shape=partialRectangle;connectable=0;fillColor=#fff2cc;strokeColor=#d6b656;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="85">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Произведенная_Продукция -->
        <!-- ========================================== -->
        <mxCell id="87" value="Произведенная_Продукция" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="1">
          <mxGeometry x="420" y="650" width="240" height="150" as="geometry" />
        </mxCell>
        <mxCell id="88" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="87">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="89" value="PK FK ID_Производства" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="88">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="90" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="87">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="91" value="PK FK ID_Продукции" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="90">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="92" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="87">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="93" value="Количество_выпущено" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="92">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="94" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#e1d5e7;strokeColor=#9673a6;" vertex="1" parent="87">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="95" value="Ед_изм" style="shape=partialRectangle;connectable=0;fillColor=#e1d5e7;strokeColor=#9673a6;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="94">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Таблица: Расход_Материалов -->
        <!-- ========================================== -->
        <mxCell id="96" value="Расход_Материалов" style="shape=table;startSize=30;container=1;collapsible=0;childLayout=tableLayout;fixedRows=1;rowLines=1;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="1">
          <mxGeometry x="820" y="650" width="240" height="150" as="geometry" />
        </mxCell>
        <mxCell id="97" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="96">
          <mxGeometry y="30" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="98" value="PK FK ID_Производства" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="97">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="99" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="96">
          <mxGeometry y="60" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="100" value="PK FK ID_Материала" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;fontStyle=1" vertex="1" parent="99">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="101" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="96">
          <mxGeometry y="90" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="102" value="Количество_списано" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="101">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="103" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;right=0;bottom=0;collapsible=0;dropTarget=0;fillColor=#f8cecc;strokeColor=#b85450;" vertex="1" parent="96">
          <mxGeometry y="120" width="240" height="30" as="geometry" />
        </mxCell>
        <mxCell id="104" value="Ед_изм" style="shape=partialRectangle;connectable=0;fillColor=#f8cecc;strokeColor=#b85450;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;" vertex="1" parent="103">
          <mxGeometry x="0" width="240" height="30" as="geometry" />
        </mxCell>

        <!-- ========================================== -->
        <!-- Связи (линии) -->
        <!-- ========================================== -->
        
        <!-- Заказчики -> Заказы (1:N) -->
        <mxCell id="rel1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="2" target="17">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <!-- Заказы -> Состав_Заказа (1:N) -->
        <mxCell id="rel2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="17" target="30">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <!-- Продукция -> Состав_Заказа (1:N) -->
        <mxCell id="rel3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.3;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="45" target="30">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="400" y="110" />
              <mxPoint x="400" y="432" />
            </Array>
          </mxGeometry>
        </mxCell>

        <!-- Продукция -> Спецификация_Продукции (1:N) -->
        <mxCell id="rel4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.3;exitDx=0;exitDy=0;entryX=0;entryY=0.3;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="45" target="69">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <!-- Материалы -> Спецификация_Продукции (1:N) -->
        <mxCell id="rel5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.6;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="58" target="69">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <!-- Производство -> Произведенная_Продукция (1:N) -->
        <mxCell id="rel6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="78" target="87">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <!-- Продукция -> Произведенная_Продукция (1:N) -->
        <mxCell id="rel7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.7;exitDx=0;exitDy=0;entryX=0;entryY=0.7;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="45" target="87">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="700" y="170" />
              <mxPoint x="700" y="755" />
            </Array>
          </mxGeometry>
        </mxCell>

        <!-- Производство -> Расход_Материалов (1:N) -->
        <mxCell id="rel8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.3;exitDx=0;exitDy=0;entryX=0;entryY=0.3;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="78" target="96">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <!-- Материалы -> Расход_Материалов (1:N) -->
        <mxCell id="rel9" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.7;exitDx=0;exitDy=0;entryX=1;entryY=0.7;entryDx=0;entryDy=0;endArrow=ERmany;startArrow=ERone;endFill=0;startFill=0;strokeWidth=2;" edge="1" parent="1" source="58" target="96">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="800" y="170" />
              <mxPoint x="800" y="755" />
            </Array>
          </mxGeometry>
        </mxCell>

        <!-- ========================================== -->
        <!-- Легенда -->
        <!-- ========================================== -->
        <mxCell id="legend" value="&lt;b&gt;Условные обозначения:&lt;/b&gt;&lt;br&gt;PK - Первичный ключ&lt;br&gt;FK - Внешний ключ&lt;br&gt;1:N - Один ко многим&lt;br&gt;N:M - Многие ко многим" style="shape=rect;whiteSpace=wrap;html=1;fillColor=#f5f5f5;strokeColor=#666666;align=left;verticalAlign=top;fontFamily=Helvetica;fontSize=12;" vertex="1" parent="1">
          <mxGeometry x="40" y="880" width="280" height="100" as="geometry" />
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
