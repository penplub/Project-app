import 'package:flutter/material.dart';

void main() => runApp( con());

class con extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return  MaterialApp(
      title: "Power convert",
      theme: ThemeData(
          primarySwatch: Colors.green
      ),
      home: Homepage(),
    );
  }
}
class Homepage extends StatefulWidget {
  @override
  _HomepageState createState() => _HomepageState();
}

class _HomepageState extends State<Homepage> {
  double  answer=0, se1=0,se2=0,se3=0,se4=0,se5=0,se6=0,se7 =0;
  num num1 = 0,num2=0;
  String momo = (""),momo2 = (""),momo3 = (""),momo4 = (""),momo5 = (""),momo6 = (""),momo7 = ("");
  String mo=(""), mo2=(""), mo3=(""), mo4=(""), mo5=(""), mo6=(""), mo7=(""), mo8=(""), mo9=(""), mo10=(""), mo11=(""), mo12=(""), mo13=("");
  dynamic _value,_value2;
  dynamic mul = (""), mul2 = (""), mul3 = (""), mul4 = (""), mul5 = (""), mul6 = (""), mul7 = (""), mul8 = ("");
  double s1=0,s2=0,s3=0,s4=0,s5=0,s6=0,s7=0,s8=0,s9=0,s10=0,s11=0,s12=0,s13=0;
  dynamic ans= (""),ans2= (""),ans3= (""),ans4= (""),ans5= (""),ans6= (""),ans7= (""),ans8= (""),ans9= (""),ans10= (""),ans11= (""),ans12= (""),ans13= ("");

  get _bird => null;

  get _salutations => null;

  void add() {
    setState(() {
      mul = num1 * se1;
      mul2= num1*se2;
      mul3 = num1*se3;
      mul4 = num1*se4;
      mul5 = num1*se5;
      mul6 = num1*se6;
      mul7 =num1*se7;


    });
  }
  void add2(){
    setState(() {
      ans = num2*s1;
      ans2 = num2*s2;
      ans3 = num2*s3;
      ans4 = num2*s4;
      ans5 = num2*s5;
      ans6 = num2*s6;
      ans7 = num2*s7;
      ans8 = num2*s8;
      ans9 = num2*s9;
      ans10 = num2*s10;
      ans11 = num2*s11;
      ans12 = num2*s12;
      ans13 = num2*s13;
    });
  }

  void select() {
    setState(() {
      se1 = 140;
      se2= 171.23 ;
      se3 = 8.74 ;
      se4 = 10.82 ;
      se5 =  14.20 ;
      se6 =  695.88 ;
      momo = "  mmsfd";
      momo2 = "  ISO Tank/day";
      momo3 = "  No. of Q-Max/year";
      momo4="  No. of Q-Flex/year";
      momo5 = "  No. of Conevetional/year";
      momo6= "  MW (Power Plant)";
    });
  }
  void select2() {
    setState(() {
      se1 =  0.007143 ;
      se2=  1.22  ;
      se3 = 0.062438 ;
      se4 = 0.077304  ;
      se5 =  0.101461 ;
      se6 =  4.97 ;
      momo = "  MTPA";
      momo2 = "  ISO Tank/day";
      momo3 = "  No. of Q-Max/year";
      momo4="  No. of Q-Flex/year";
      momo5 = "  No. of Conevetional/year";
      momo6= "  MW (Power Plant)";


    });
  }
  void select3() {
    setState(() {
      se1 =  0.005840 ;
      se2= 0.82 ;
      se3 = 0.051049 ;
      se4 = 0.063203 ;
      se5 = 0.082955 ;
      se6 =  4.06  ;
      momo = "  MTPA";
      momo2 = "  mmsfd";
      momo3 = "  No. of Q-Max/year";
      momo4="  No. of Q-Flex/year";
      momo5 = "  No. of Conevetional/year";
      momo6= "  MW (Power Plant)";
    });
  }
  void select4() {
    setState(() {
      se1 = 0.114400 ;
      se2= 16.02 ;
      se3 = 19.59  ;
      se4 = 1.24 ;
      se5 = 1.63;
      se6 = 79.61;
      momo = "  MTPA";
      momo2 = "  mmsfd";
      momo3 = "  ISO Tank/day";
      momo4="  No. of Q-Flex/year";
      momo5 = "  No. of Conevetional/year";
      momo6= "  MW (Power Plant)";
    });
  }
  void select5() {
    setState(() {
      se1 = 0.092400 ;
      se2= 12.94 ;
      se3= 15.82;
      se4 =  0.807692;
      se5 = 1.31;
      se6=  64.30;
      momo = "  MTPA";
      momo2 = "  mmsfd";
      momo3 = "  ISO Tank/day";
      momo4="  No. of Q-Max/year";
      momo5 = "  No. of Conevetional/year";
      momo6= "  MW (Power Plant)";
    });
  }
  void select7() {
    setState(() {
      se1 = 0.001437 ;
      se2= 0.201185 ;
      se3 =  0.25 ;
      se4 = 0.012562 ;
      se5 = 0.015552 ;
      se6= 0.02;
      momo = "  MTPA";
      momo2 = " mmsfd";
      momo3 = "  ISO Tank/day";
      momo4="  No. of Q-Max/year";
      momo5 = "  No. of Q-Flex/year";
      momo6= "  No. of Conevetional/year";
    });
  }
  void select6() {
    setState(() {
      se1 =  0.070400 ;
      se2=  9.86  ;
      se3 = 12.05 ;
      se4 = 0.615385;
      se5 =  0.761905;
      se6 =  48.99  ;
      momo = "  MTPA";
      momo2 = "  mmsfd";
      momo3 = "  ISO Tank/day";
      momo4="  No. of Q-Max/year";
      momo5 = "  No. of Q-Flex/year";
      momo6= "  MW (Power Plant)";
    });
  }
  void su() {
    setState(() {
      s1 = 0.028316847;
      s2=  0.00004447607187 ;
      s3 = 0.00001956947162;
      s4 = 0.001017613;
      s5 = 0.00002564547693;
      s6 =0.00017545 ;
      s7 = 1074 ;
      s8 =0.298232791 ;
      s9 =0.000001223091977 ;
      s10 =0.0000000001710618149 ;
      s11 =0.0000000002117908184 ;
      s12 =0.0000000002779754492 ;
      mo = "  scm";
      mo2 = "  LNG m3";
      mo3 = "  Tonne";
      mo4="  MMBtu";
      mo5 = "  toe";
      mo6= "  boe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su2() {
    setState(() {
      s1 =35.3146667;
      s2= 0.001570657654 ;
      s3 = 0.0006910893679;
      s4 = 0.03593664713;
      s5 = 0.00090566147;
      s6 =0.006195973643 ;
      s7 =   37915 ;
      s8 =  11  ;
      s9 =0.00004319308549;
      s10 =0.000000006040990978 ;
      s11 =0.000000007479322163 ;
      s12 =0.00000000981661034 ;
      mo = "  scf";
      mo2 = "  LNG m3";
      mo3 = "  Tonne";
      mo4="  MMBtu";
      mo5 = "  toe";
      mo6= "  boe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su3() {
    setState(() {
      s1 =  22484 ;
      s2=   637 ;
      s3 = 0.44;
      s4 =   23 ;
      s5 = 0.5766129032;
      s6 =3.944827586;
      s7 =   24139678 ;
      s8 =   6705  ;
      s9 =0.0275;
      s10 =0.000003846153846 ;
      s11 =0.000004761904762 ;
      s12 =0.00000625;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  Tonne";
      mo4="  MMBtu";
      mo5 = "  toe";
      mo6= "  boe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su4() {
    setState(() {
      s1 =    51100  ;
      s2=   1447  ;
      s3 = 2.272727273;
      s4 =     52  ;
      s5 = 1.310483871;
      s6 =8.965517241;
      s7 =    54862904  ;
      s8 =    15240   ;
      s9 =0.0625;
      s10 =0.000008741258741 ;
      s11 =0.00001082251082 ;
      s12 =0.00001420454545;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  MMBtu";
      mo5 = "  toe";
      mo6= "  boe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su5() {
    setState(() {
      s1 =  982.6923077  ;
      s2=   27.82674734 ;
      s3 = 0.04370629371;
      s4 = 0.01923076923 ;
      s5 = 0.0252016129;
      s6 =0.1724137931;
      s7 =   1055056   ;
      s8 =   293  ;
      s9 =0.001201923077;
      s10 =0.0000001681011296 ;
      s11 =0.0000002081252081 ;
      s12 =0.0000002731643357;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  toe";
      mo6= "  boe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank :";
      mo10 ="  No. of Q-Max :" ;
      mo11 ="  No. of Q-Flex :";
      mo12="  No. of Conevetional" ;
    });
  }
  void su6() {
    setState(() {
      s1 =   38993  ;
      s2=   1104  ;
      s3 =1.734265734;
      s4 = 0.7630769231 ;
      s5 = 39.68;
      s6 =  7 ;
      s7 =   41864616  ;
      s8 =  11629  ;
      s9 =0.04769230769;
      s10 =0.000006670252824 ;
      s11 =0.000008258408258 ;
      s12 =0.00001083916084;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  boe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su7() {
    setState(() {
      s1 =   5700 ;
      s2=   161  ;
      s3 =0.2534965035;
      s4 = 0.1115384615 ;
      s5 =  5.80 ;
      s6 =0.1461693548;
      s7 =   6119324 ;
      s8 =   1700  ;
      s9 =0.006971153846;
      s10 =0.0000009749865519;
      s11 =0.000001207126207 ;
      s12 =0.000001584353147;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "   MMBtu";
      mo6= "  toe";
      mo7 ="  kJ" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su8() {
    setState(() {
      s1 = 0.0009314125938;
      s2= 0.00002637466755 ;
      s3 =0.00000004142557346;
      s4 =0.00000001822725232;
      s5 =0.0000009478171209;
      s6 =0.00000002388652018;
      s7 =0.000000163416745;
      s8 =0.0002777777778 ;
      s9 =0.00000000113920327;
      s10 =0;
      s11 =0 ;
      s12 =0;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  toe";
      mo7 ="  boe" ;
      mo8 ="  kWh";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su9() {
    setState(() {
      s1 = 3.353085338;
      s2= 0.09494880317;
      s3 =0.0001491320645;
      s4 =0.00006561810837;
      s5 =0.003412141635;
      s6 =0.00008599147266;
      s7 =0.0005883002819;
      s8 =  3600 ;
      s9 =0.000004101131773;
      s10 =0.0000000005735848634;
      s11 =0.000000000710152688;
      s12 =0.000000000932075403;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  toe";
      mo7 ="  boe" ;
      mo8 ="  kJ";
      mo9 ="  ISO Tank";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su10() {
    setState(() {
      s1 =  817600 ;
      s2=   23152 ;
      s3 =36.36363636;
      s4 =  16 ;
      s5 =  832 ;
      s6 =20.96774194;
      s7 =  143 ;
      s8 =  877806468.86  ;
      s9 =243835.1302;
      s10 =0.00000003885003885;
      s11 =0.0000000481000481;
      s12 =0.00000006313131313;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  toe";
      mo7 ="  boe" ;
      mo8 ="  kJ";
      mo9 ="  kWh";
      mo10 ="  No. of Q-Max" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su11() {
    setState(() {
      s1 =5845840000;
      s2=   165535755  ;
      s3 =  260000 ;
      s4 =   114400 ;
      s5 =  5948800 ;
      s6 =  149919 ;
      s7 =  1025655  ;
      s8 =6276316252378;
      s9 =1743421181;
      s10 =  25740000 ;
      s11 =1.238095238;
      s12 =1.625;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  toe";
      mo7 ="  boe" ;
      mo8 ="  kJ";
      mo9 ="  kWh";
      mo10 ="  ISO Tank" ;
      mo11 ="  No. of Q-Flex";
      mo12="  No. of Conevetional" ;
    });
  }
  void su12() {
    setState(() {
      s1 =4721640000;
      s2=   133701956 ;
      s3 =   210000 ;
      s4 =   92400 ;
      s5 =  4804800 ;
      s6 =    121089  ;
      s7 =  828414 ;
      s8 =5069332357690;
      s9 =1408147877;
      s10 =   20790000  ;
      s11 =0.8076923077;
      s12 =1.3125;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  toe";
      mo7 ="  boe" ;
      mo8 ="  kJ";
      mo9 ="  kWh";
      mo10 ="  ISO Tank" ;
      mo11 ="  No. of Q-Max";
      mo12="  No. of Conevetional" ;
    });
  }
  void su13() {
    setState(() {
      s1 =3597440000;
      s2=    101868157  ;
      s3 =   160000 ;
      s4 =   70400 ;
      s5 =  3660800  ;
      s6 =   92258   ;
      s7 =   631172 ;
      s8 =3862348463002;
      s9 =1072874573;
      s10 =   15840000 ;
      s11 =0.6153846154;
      s12 =0.7619047619;
      mo = "  scf";
      mo2 = "  scm";
      mo3 = "  LNG m3";
      mo4="  Tonne";
      mo5 = "  MMBtu";
      mo6= "  toe";
      mo7 ="  boe" ;
      mo8 ="  kJ";
      mo9 ="  kWh";
      mo10 ="  ISO Tank" ;
      mo11 ="  No. of Q-Max";
      mo12="  No. of Q-Flex" ;
    });
  }


  @override
  Widget build(BuildContext context) {
    return Scaffold(
      resizeToAvoidBottomInset: false,
      appBar: AppBar(
        title: Text("Convert"),
        centerTitle: true,
      ),
      body: Container(
          child: Padding(
            padding: const EdgeInsets.only(top:30,left: 30,bottom: 30),
            child: SingleChildScrollView(
              padding: EdgeInsets.all(32),
              child: Column(
                  mainAxisAlignment: MainAxisAlignment.start,
                  crossAxisAlignment: CrossAxisAlignment.start,
                  children: <Widget>[
                    Text("Quantity / time" ,style: TextStyle(fontSize:40),),
                    DropdownButton<String>(



                      items: [

                        DropdownMenuItem<String>(
                          child: Text('None'),
                          value: 'one',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('MTPA'),
                          value: 'two',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('mmscfd'),
                          value: 'three',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('ISO Tank/day'),
                          value: 'four',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('No. of Q-Max/year'),
                          value: 'five',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('No. of Q-Flex/year'),
                          value: 'six',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('No. of Conevetional/year'),
                          value: 'seven',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('MW (Power Plant)'),
                          value: 'eight',
                        ),
                      ],
                      onChanged: (String? value) {
                        setState(() {

                          _value = value!;
                          if (value == 'one') {


                          }
                          else if (value == 'two') {
                            select();

                          }
                          else if (value == 'three') {
                            select2();
                          }
                          else if (value == 'four') {
                            select3();
                          }
                          else if (value == 'five') {
                            select4();
                          }
                          else if (value == 'six') {
                            select5();
                          }
                          else if (value == 'seven') {
                            select6();
                          }
                          else if (value == 'eight') {
                            select7();
                          }
                        });

                      },
                      hint: Text('Select Item'),
                      value: _value,
                    ),
                    TextField(
                      keyboardType: TextInputType.number,
                      decoration: InputDecoration(hintText: 'Enter first quantity/time'),
                      onChanged: (value) {
                        setState(() {
                          num1 = num.parse(value);
                        });
                      },
                    ),
                    SizedBox(
                      height: 20.0,
                    ),


                    Row(
                      mainAxisAlignment: MainAxisAlignment.spaceBetween,
                      children: <Widget>[
                        RaisedButton(
                          color: Colors.indigo,
                          child: Text(
                            'convert',
                            style: TextStyle(color: Colors.white),
                          ),
                          onPressed: () {
                            add();
                          },
                        ),
                      ],
                    ),
                    SizedBox(
                      height: 20.0,
                    ),
                    Text( '$mul'+momo ,style: TextStyle(fontSize:20),),
                    Text( '$mul2'+momo2,style: TextStyle(fontSize:20),),
                    Text( '$mul3'+momo3,style: TextStyle(fontSize:20),),
                    Text( '$mul4'+momo4,style: TextStyle(fontSize:20),),
                    Text( '$mul5'+momo5,style: TextStyle(fontSize:20),),
                    Text( '$mul6'+momo6,style: TextStyle(fontSize:20),),
                    SizedBox(
                      height: 40.0,
                    ),
                    Text("Quantity",style: TextStyle(fontSize:40),),
                    DropdownButton<String>(
                      items: [

                        DropdownMenuItem<String>(
                          child: Text('None'),
                          value: '1',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('scf'),
                          value: '2',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('scm'),
                          value: '3',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('LNG m3'),
                          value: '4',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('Tonne'),
                          value: '5',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('MMBtu'),
                          value: '6',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('toe'),
                          value: '7',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('boe'),
                          value: '8',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('kJ'),
                          value: '9',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('kWh'),
                          value: '10',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('ISO Tank'),
                          value: '11',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('No. of Q-Max'),
                          value: '12',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('No. of Q-Flex'),
                          value: '13',
                        ),
                        DropdownMenuItem<String>(
                          child: Text('No. of  Conevetional'),
                          value: '14',
                        ),
                      ],
                      onChanged: (String? val) {
                        setState(() {

                          _value2 = val!;

                          if (val == '1') {

                          } else if (val == '2') {
                            su();

                          }
                          else if (val == '3') {
                            su2();
                          }
                          else if (val == '4') {
                            su3();
                          }
                          else if (val == '5') {
                            su4();
                          }
                          else if (val == '6') {
                            su5();
                          }
                          else if (val == '7') {
                            su6();
                          }
                          else if (val == '8') {
                            su7();
                          }
                          else if (val == '9') {
                            su8();
                          }
                          else if (val == '10') {
                            su9();
                          }
                          else if (val == '11') {
                            su10();
                          }
                          else if (val == '12') {
                            su11();
                          }
                          else if (val == '13') {
                            su12();
                          }
                          else if (val == '14') {
                            su13();
                          }


                        });

                      },
                      hint: Text('Select Item'),
                      value: _value2,
                    ),

                    TextField(
                      keyboardType: TextInputType.number,
                      decoration: InputDecoration(hintText: 'Enter first quantity'),
                      onChanged: (value) {
                        setState(() {
                          num2 = num.parse(value);
                        });
                      },
                    ),

                    SizedBox(
                      height: 20.0,
                    ),

                    Row(
                      mainAxisAlignment: MainAxisAlignment.spaceBetween,
                      children: <Widget>[
                        RaisedButton(
                          color: Colors.indigo,
                          child: Text(
                            'convert',
                            style: TextStyle(color: Colors.white),
                          ),
                          onPressed: () {
                            add2();
                          },
                        ),

                      ],
                    ),
                    SizedBox(
                      height: 20.0,
                    ),
                    Text( '$ans'+mo,style: TextStyle(fontSize:20),),
                    Text( '$ans2'+mo2,style: TextStyle(fontSize:20),),
                    Text( '$ans3'+mo3,style: TextStyle(fontSize:20),),
                    Text( '$ans4'+mo4,style: TextStyle(fontSize:20),),
                    Text( '$ans5'+mo5,style: TextStyle(fontSize:20),),
                    Text( '$ans6'+mo6,style: TextStyle(fontSize:20),),
                    Text( '$ans7'+mo7,style: TextStyle(fontSize:20),),
                    Text( '$ans8'+mo8,style: TextStyle(fontSize:20),),
                    Text( '$ans9'+mo9,style: TextStyle(fontSize:20),),
                    Text( '$ans10'+mo10,style: TextStyle(fontSize:20),),
                    Text( '$ans11'+mo11,style: TextStyle(fontSize:20),),
                    Text( '$ans12'+mo12,style: TextStyle(fontSize:20),),


                  ]),
            ),
          )),
    );
  }
}


