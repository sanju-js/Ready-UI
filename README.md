Specify JSon
var sec=
{
batch:{domtyp:'input_styl2',dom:'',type:'text',val:'',lbl:"BATCH",col_siz:3,color:'black'},
grp:{domtyp:'input_styl2',dom:'',type:'select',val:'',lbl:"GROUP",col_siz:3,color:'black'},
d1:{domtyp:'input_styl2',dom:'',type:'date',val:'',lbl:"DATE FROM",col_siz:3,chkbox:1,color:'black'},
dis:{domtyp:'input_styl2',dom:'',type:'text',val:'',lbl:"DIS1",col_siz:1,color:'black'},
butn:{domtyp:"ui_col",dom:"",type:"button",val:"SAVE",col_siz:8,color:"coral"},
}

var dv=ui_col_blank(document.body,12,'max-width:700px;min-height:100%;padding:20px;background:white;border:1px solid gray;')
var row=ui_col_blank(dv,12,'padding:0px;background:transparent;border:0px solid gray;')
var ui=Reusable_UI1(sec,row)
