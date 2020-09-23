<div align="center">

## Cool Java Applet


</div>

### Description

This applet reads in messages from a text file and displays them in different ways.
 
### More Info
 
//conf.dat

<news caption="RAC" content="RentACoder is the place to search for extra programming jobs."

url="http://www.rentacoder.com">

<news caption="PSC" content="Planet-Source-

Code.com is the place to post and check out other

peoples source codes" url="http://www.planet-source-code.com">


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[darocker22](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/darocker22.md)
**Level**          |Intermediate
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\)
**Category**       |[Applet](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/applet__2-81.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/darocker22-cool-java-applet__2-2621/archive/master.zip)

### API Declarations

```
<!doctype html public "-//w3c//dtd html 4.0 transitional//en">
<html>
<head>
  <title>Java Applet</title>
</head>
<body>
<br>
<center>
<p><b><font color="#FF0000"><font size=+1>Installation</font></font></b></center>
&nbsp;
<center><table BORDER=0 CELLSPACING=0 CELLPADDING=0 COLS=2 WIDTH="80%" >
<tr>
<td VALIGN=TOP WIDTH="30%"><TABLE WIDTH=100%><TR><TD>
	<applet code="message.class"
    align="baseline" width="136" height="160"><param
    name="notice" value="Copyright(c) 2002, DAROCKER22"><param
    name="license" value="Demo"><param name="bgcolor"
    value="255, 255, 255"><param name="fgcolor"
    value="0, 0, 122"><param name="hgcolor" value="255, 0, 0"><param
    name="ovcolor" value="255, 0, 255"><param name="pscolor"
    value="125, 155, 177"><param name="font"
    value="serif, PLAIN, 16"><param name="bar_size"
    value="15"><param name="window" value="_parent"></applet></td></TR></TABLE>
<td WIDTH="100%"><TABLE BORDER=1 BGCOLOR="#EEEEEE" CELLSPACING=0 CELLPADDING=0
BORDERCOLORLIGHT=000000 BORDERCOLORDARK=FFFFFF><TR><TD><font color="#000000">Install
following
files in the same directory as your HTML file and set file permission correctly
for Internet access&nbsp;</font>
<ul>
<li>
<font color="#000000">message.class</font></li>
<li>
<font color="#000000">conf.dat</font></li>
</ul>
<font color="#000000">All news information are stored in a file called
<i>"conf.dat"</i>,&nbsp; this file format is pretty much like HTML format,
you can use any text editor tool to generate this file,&nbsp; in order
to let applet parse it properly, this file must comply with some guidelines.
Each news entry is defined by tags values and must be in the same line,
namely, do not punch ENTER key in middle of news entry, any blank lines
and lines starting with "&lt;!" are skipped. Take a look at following sample
<i>"conf.dat"</i> file.&nbsp;</font></td>
</tr>
</table></center>
</TD></TR></TABLE>
<hr size="1">
<center>
<p><b><font color="#FF0000"><font size=+1>Sample "conf.dat" file</font></font></b></center>
&nbsp;
<center><table BORDER=1 CELLSPACING=0 CELLPADDING=0 COLS=1 WIDTH="80%" BGCOLOR="#EEEEEE"
BORDERCOLORLIGHT=000000 BORDERCOLORDARK=FFFFFF>
<tr>
<td>&lt;!--This is a sample configuration file for message applet>&nbsp;
<p>&lt;!-- Each news entry has three parts: caption, news content and URL
link. There is at least one space between each part and news entry must
be in the same line, URL link can be either relative to current codebase
or absolute>
<p>&lt;news caption="RAC" content="RentACoder is the place to search for extra programming
jobs." url="http://www.rentacoder.com">
<p>&lt;news caption="PSC" content="Planet-Source-Code.com is the place to post and check out
other peoples source codes" url="http://www.planet-source-code.com">
</td>
</tr>
</table></center>
<hr size="1">
<center>
<p><b><font color="#FF0000"><font size=+1>Applet parameters</font></font></b></center>
&nbsp;
<center><table BORDER COLS=2 WIDTH="80%" CELLSPACING=0 CELLPADDING=0 BGCOLOR="#EEEEEE"
BORDERCOLORLIGHT=000000 BORDERCOLORDARK=FFFFFF>
<tr>
<td WIDTH="10%" BGCOLOR="#3333FF"><b><font color="#FFFFFF">Name</font></b></td>
<td BGCOLOR="#3333FF"><b><font color="#FFFFFF">Description</font></b></td>
</tr>
<tr>
<td WIDTH="8%"><b>notice</b></td>
<td>This&nbsp; mandatory parameter must be explicitly included, otherwise
message applet will not work.&nbsp;
<p><b>Usage:</b>
<br>&lt;param name="notice" value="Copyright (C) 2002, DAROCKER22">&nbsp;</td>
</tr>
<tr>
<td><b>license</b></td>
<td>This mandatory parameter must be explicitly included, otherwise message
applet will not work.&nbsp;
<p><b>Usage:</b>
<br>&lt;param name="license" value="Demo">&nbsp;</td>
</tr>
<tr>
<td><b>window&nbsp;</b></td>
<td>Defines name of a frame or a window where links will be opened. There
are 5 choices for this parameter&nbsp;
<ul>
<li>
"_self":&nbsp; open page in current window</li>
<li>
"_parent":&nbsp;&nbsp; open page in parent window</li>
<li>
&nbsp;"_top":&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; open page in topmost window</li>
<li>
"_blank":&nbsp;&nbsp;&nbsp; open page in new unnamed top-level window</li>
<li>
name: open page in a new top-level window called <i>name&nbsp;</i></li>
</ul>
<b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="window" vaule="_self">&nbsp;</td>
</tr>
<tr>
<td><b>bgcolor</b></td>
<td>Applet background color using RGB triplet of 3 decimal numbers in the
range of 0-255.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="bgcolor"&nbsp; value="255, 0, 0"></td>
</tr>
<tr>
<td><b>bdcolor</b></td>
<td>Applet border color using RGB triplet of 3 decimal numbers in the range
of 0-255.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="bdcolor"&nbsp; value="255, 0, 0"></td>
</tr>
<tr>
<td><b>speed</b></td>
<td>Text scroll speed (in milliseconds).&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="speed"&nbsp; value="20"></td>
</tr>
<tr>
<td><b>mocolor</b></td>
<td>News content color using RGB triplet of 3 decimal numbers in the range
of 0-255 when mouse is over news content area,.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="mocolor"&nbsp; value="255, 0, 0"></td>
</tr>
<tr>
<td><b>delay</b></td>
<td>Delay time between two news (in millisecond)&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="delay"&nbsp; value="2000"></td>
</tr>
<tr>
<td><b>cap_font</b></td>
<td>News caption font characteristic using triplet of font name, font style
and font size.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="cap_font"&nbsp; value="serif, plain, 12"></td>
</tr>
<tr>
<td><b>cap_color&nbsp;</b></td>
<td>News caption color using RGB triplet of 3 decimal numbers in the range
of 0-255.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="cap_color"&nbsp; value="255, 0, 0"></td>
</tr>
<tr>
<td><b>txt_font</b></td>
<td>News content font characteristic using triplet of font name, font style
and font size.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="txt_font"&nbsp; value="serif, plain, 12"></td>
</tr>
<tr>
<td><b>txt_color&nbsp;</b></td>
<td>News content color using RGB triplet of 3 decimal numbers in the range
of 0-255.&nbsp;
<p><b>Sample Usage:</b>
<br><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>&lt;param
name="txt_color"&nbsp; value="255, 0, 0"></td>
</tr>
</table></center>
<hr size="1">
<center>
<p><b><font color="#FF0000"><font size=+1>Sample Applet Tag in HTML
file</font></font></b></center>
<center><table BORDER=1 COLS=1 WIDTH="80%" ELLSPACING=0 CELLPADDING=0 BGCOLOR="#EEEEEE"
BORDERCOLORLIGHT=000000 BORDERCOLORDARK=FFFFFF>
<tr>
<td>&lt;applet code="Hscroll.class" width="136" height="200">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="notice"
value="Copyright(c) 2002, DAROCKER22">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="license"
value="Demo">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="bgcolor"
value="0, 255, 0">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="bdcolor"
value="0, 255, 0">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="mocolor"
value="0, 255, 0">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="txt_color"
value="255, 255, 255">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="txt_font"
value="Courier, ITALIC, 14">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="cap_color"
value="255, 255, 255">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="cap_font"
value="Courier, ITALIC, 14">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="speed" value="55">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="delay" value="155">
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;param name="window"
value="_parent">
<br>&lt;/applet></td>
</tr>
</table></center>
<br>&nbsp;
<br>&nbsp;
<br>&nbsp;
<br>&nbsp;
<br>&nbsp;
</body>
</html>
```


### Source Code

```

import java.applet.Applet;
import java.applet.AppletContext;
import java.awt.*;
import java.io.DataInputStream;
import java.io.PrintStream;
import java.net.URL;
import java.util.StringTokenizer;
import java.util.Vector;
public class message extends Applet
  implements Runnable
{
  Thread display;
  String message;
  int message_pos;
  int caption_pos;
  int pos;
  int offset;
  int select_index;
  Vector all_urls;
  Vector all_news;
  Vector all_caps;
  Vector all_rects;
  Vector back_rects;
  Vector news_group;
  boolean legal;
  Color cap_fgcolor;
  Font capfont;
  Color bgcolor;
  Color fgcolor;
  Font txtfont;
  Color bdcolor;
  Color mocolor;
  int speed;
  int delay;
  String window;
  int font_size;
  FontMetrics fm;
  boolean mouse_in;
  int max_select_index;
  int total_height;
  int total_chars;
  int nor_h;
  int nor_a;
  int cap_h;
  int cap_a;
  boolean done;
  Dimension d;
  Dimension offDimension;
  Image offImage;
  Graphics offGraphics;
  Point mouse_point;
  public void init()
  {
    pos = 0;
    d = size();
    try
    {
      String s = getParameter("notice");
      if(s.indexOf("DAROCKER22") < 0)
        legal = false;
      if(s.indexOf("Copyright") < 0)
        legal = false;
      s = getParameter("license");
      if(!s.equals("Demo"))
        legal = false;
    }
    catch(Exception _ex)
    {
      legal = false;
    }
    Color color = null;
    color = get_color("bgcolor");
    if(color != null)
      bgcolor = color;
    color = get_color("txt_color");
    if(color != null)
      fgcolor = color;
    color = get_color("cap_color");
    if(color != null)
      cap_fgcolor = color;
    color = get_color("bdcolor");
    if(color != null)
      bdcolor = color;
    color = get_color("mocolor");
    if(color != null)
      mocolor = color;
    Font font = get_font("txt_font");
    if(font != null)
      txtfont = font;
    font = get_font("cap_font");
    if(font != null)
      capfont = font;
    String s1 = getParameter("speed");
    if(s1 != null)
    {
      Integer integer = new Integer(remove_space(s1));
      speed = integer.intValue();
    }
    s1 = getParameter("delay");
    if(s1 != null)
    {
      Integer integer1 = new Integer(remove_space(s1));
      delay = integer1.intValue();
    }
    s1 = getParameter("window");
    if(s1 != null)
      window = s1;
    setBackground(bgcolor);
    fm = getToolkit().getFontMetrics(txtfont);
    nor_h = fm.getHeight();
    nor_a = fm.getAscent();
    fm = getToolkit().getFontMetrics(capfont);
    cap_h = fm.getHeight();
    cap_a = fm.getAscent();
    DataInputStream datainputstream = null;
    try
    {
      URL url = new URL(getCodeBase(), "conf.dat");
      java.io.InputStream inputstream = url.openStream();
      datainputstream = new DataInputStream(inputstream);
    }
    catch(Exception _ex) { }
    int i = 0;
    try
    {
      for(String s2 = datainputstream.readLine(); s2 != null; s2 = datainputstream.readLine())
      {
        i = s2.indexOf("<news ");
        if(i >= 0)
        {
          news_group.addElement(new String(" "));
          String s3 = s2.substring(i + 5);
          i = s3.lastIndexOf(">");
          s3 = s3.substring(0, i);
          i = s3.indexOf("caption=");
          s3 = s3.substring(i);
          all_caps.addElement(get_next_string(s3));
          i = s3.indexOf("content=");
          s3 = s3.substring(i);
          all_news.addElement(get_next_string(s3));
          i = s3.indexOf("url=");
          s3 = s3.substring(i);
          all_urls.addElement(parse_url(get_next_string(s3)));
        }
      }
    }
    catch(Exception exception)
    {
      System.out.println(exception);
    }
    i = 0;
    mouse_point = new Point(-1, -1);
  }
  public String get_next_string(String s)
  {
    int i = s.indexOf(34);
    String s1 = s.substring(i + 1);
    i = s1.indexOf(34);
    return s1.substring(0, i);
  }
  public boolean handleEvent(Event event)
  {
    if(!done)
      return super.handleEvent(event);
    switch(event.id)
    {
    case 504: // Event.MOUSE_EVENT
      mouse_in = true;
      Thread.yield();
      repaint();
      display.resume();
      break;
    case 505: // Event.MOUSE_EXIT
      mouse_in = false;
      Thread.yield();
      repaint();
      display.resume();
      break;
    case 501: // Event.MOUSE_DOWN
      mouse_pressed(event);
      break;
    }
    return super.handleEvent(event);
  }
  public void mouse_pressed(Event event)
  {
    int i = event.x;
    int j = event.y;
    mouse_point = new Point(i, j);
    String s = (String)all_urls.elementAt(pos);
    try
    {
      URL url = new URL(s);
      getAppletContext().showDocument(url, window);
      return;
    }
    catch(Exception _ex)
    {
      return;
    }
  }
  public void paint(Graphics g)
  {
    update(g);
  }
  public void update(Graphics g)
  {
    if(!legal)
      return;
    if(all_news.size() == 0)
      return;
    d = size();
    if(offImage == null)
    {
      offDimension = size();
      offImage = createImage(d.width, d.height);
      offGraphics = offImage.getGraphics();
    }
    offGraphics.clearRect(0, 0, d.width, d.height);
    offGraphics.setColor(bgcolor);
    offGraphics.fillRect(0, 0, d.width, d.height);
    offGraphics.setColor(bdcolor);
    offGraphics.drawRect(0, 0, d.width - 1, d.height - 1);
    int i = (pos + 1) % all_caps.size();
    String s = (String)all_caps.elementAt(i);
    String s1 = (String)all_news.elementAt(i);
    Vector vector = new Vector();
    vector = parse_lines(parse_words(s1));
    vector.insertElementAt(s, 0);
    int j = (vector.size() - 1) * nor_h + cap_h;
    j = (d.height - j) / 2;
    int k = j + nor_h;
    boolean flag = false;
    for(int j1 = 0; j1 < vector.size(); j1++)
    {
      String s2 = (String)vector.elementAt(j1);
      if(j1 == 0)
      {
        k += cap_a;
        fm = getToolkit().getFontMetrics(capfont);
        int l = fm.stringWidth(s2);
        l = (d.width - l) / 2;
        offGraphics.setFont(capfont);
        offGraphics.setColor(cap_fgcolor);
        offGraphics.drawString(s2, l, k);
      } else
      {
        k += nor_a;
        fm = getToolkit().getFontMetrics(txtfont);
        int i1 = fm.stringWidth(s2);
        i1 = (d.width - i1) / 2;
        offGraphics.setFont(txtfont);
        if(mouse_in)
          offGraphics.setColor(mocolor);
        else
          offGraphics.setColor(fgcolor);
        offGraphics.drawString(s2, i1, k);
      }
    }
    g.drawImage(offImage, 0, 0, this);
  }
  public String parse_url(String s)
  {
    if(s.indexOf("http://") >= 0)
      return s;
    URL url = null;
    try
    {
      url = getCodeBase();
    }
    catch(Exception _ex) { }
    String s1 = url.getHost();
    String s2 = url.getFile();
    s = remove_space(s);
    if(s.startsWith("/"))
      return "http://" + s1 + s;
    if(s.startsWith("../"))
    {
      for(int i = s.indexOf("../"); i >= 0; i = s.indexOf("../"))
      {
        s = s.substring(i + 3);
        i = s2.lastIndexOf("/");
        s2 = s2.substring(0, i);
      }
      int j = s2.lastIndexOf("/");
      s2 = s2.substring(0, j);
      return "http://" + s1 + s2 + "/" + s;
    } else
    {
      int k = s2.lastIndexOf("/");
      s2 = s2.substring(0, k + 1);
      return "http://" + s1 + s2 + s;
    }
  }
  public Vector parse_words(String s)
  {
    Vector vector = new Vector();
    StringBuffer stringbuffer = new StringBuffer();
    for(int i = 0; i < s.length(); i++)
    {
      char c = s.charAt(i);
      if(c != ' ')
      {
        stringbuffer.append(c);
      } else
      {
        vector.addElement(new String(stringbuffer));
        stringbuffer = new StringBuffer();
      }
    }
    vector.addElement(new String(stringbuffer));
    return vector;
  }
  public void refresh(int i, int j)
  {
    Graphics g = getGraphics();
    d = size();
    if(offImage == null)
    {
      offDimension = size();
      offImage = createImage(d.width, d.height);
      offGraphics = offImage.getGraphics();
    }
    offGraphics.clearRect(0, 0, size().width, size().height);
    String s = (String)all_caps.elementAt(pos);
    String s1 = (String)all_news.elementAt(pos);
    Vector vector = new Vector();
    vector = parse_lines(parse_words(s1));
    vector.insertElementAt(s, 0);
    int k = (vector.size() - 1) * nor_h + cap_h;
    k = (d.height - k) / 2;
    int l = k + nor_h;
    boolean flag = false;
    for(int i2 = 0; i2 < vector.size(); i2++)
    {
      String s2 = (String)vector.elementAt(i2);
      if(i2 == 0)
      {
        l += cap_a;
        fm = getToolkit().getFontMetrics(capfont);
        int i1 = fm.stringWidth(s2);
        i1 = (d.width - i1) / 2;
        offGraphics.setFont(capfont);
        offGraphics.setColor(cap_fgcolor);
        offGraphics.drawString(s2, i1, l);
      } else
      {
        l += nor_a;
        fm = getToolkit().getFontMetrics(txtfont);
        int j1 = fm.stringWidth(s2);
        j1 = (d.width - j1) / 2;
        offGraphics.setFont(txtfont);
        if(mouse_in)
          offGraphics.setColor(mocolor);
        else
          offGraphics.setColor(fgcolor);
        offGraphics.drawString(s2, j1, l);
      }
    }
    int j2 = (pos + 1) % all_news.size();
    s = (String)all_caps.elementAt(j2);
    s1 = (String)all_news.elementAt(j2);
    vector = new Vector();
    vector = parse_lines(parse_words(s1));
    vector.insertElementAt(s, 0);
    k = (vector.size() - 1) * nor_h + cap_h;
    k = (d.height - k) / 2;
    l = k + nor_h;
    int k2 = 0;
    int l2 = 0;
    switch(j)
    {
    case 0: // '\0'
      k2 = d.width - (i * d.width) / 10;
      l2 = d.height - (i * d.height) / 10;
      break;
    case 1: // '\001'
      k2 = d.width - (i * d.width) / 10;
      l2 = 0;
      break;
    case 2: // '\002'
      k2 = d.width - (i * d.width) / 10;
      l2 = -d.height + (i * d.height) / 10;
      break;
    case 3: // '\003'
      k2 = 0;
      l2 = -d.height + (i * d.height) / 10;
      break;
    case 4: // '\004'
      k2 = -d.width + (i * d.width) / 10;
      l2 = -d.height + (i * d.height) / 10;
      break;
    case 5: // '\005'
      k2 = -d.width + (i * d.width) / 10;
      l2 = 0;
      break;
    case 6: // '\006'
      k2 = -d.width + (i * d.width) / 10;
      l2 = d.height - (i * d.height) / 10;
      break;
    case 7: // '\007'
      k2 = 0;
      l2 = d.height - (i * d.height) / 10;
      break;
    }
    offGraphics.setColor(bdcolor);
    offGraphics.drawRect(k2, l2, d.width - 1, d.height - 1);
    offGraphics.setColor(bgcolor);
    offGraphics.fillRect(k2 + 1, l2 + 1, d.width - 2, d.height - 2);
    for(int i3 = 0; i3 < vector.size(); i3++)
    {
      String s3 = (String)vector.elementAt(i3);
      if(i3 == 0)
      {
        l += cap_a;
        fm = getToolkit().getFontMetrics(capfont);
        int k1 = fm.stringWidth(s3);
        k1 = (d.width - k1) / 2;
        offGraphics.setFont(capfont);
        offGraphics.setColor(cap_fgcolor);
        offGraphics.drawString(s3, k2 + k1, l2 + l);
      } else
      {
        l += nor_a;
        fm = getToolkit().getFontMetrics(txtfont);
        int l1 = fm.stringWidth(s3);
        l1 = (d.width - l1) / 2;
        offGraphics.setFont(txtfont);
        if(mouse_in)
          offGraphics.setColor(mocolor);
        else
          offGraphics.setColor(fgcolor);
        offGraphics.drawString(s3, k2 + l1, l2 + l);
      }
    }
    offGraphics.setColor(bdcolor);
    offGraphics.drawRect(0, 0, d.width - 1, d.height - 1);
    g.drawImage(offImage, 0, 0, this);
  }
  public String remove_space(String s)
  {
    StringBuffer stringbuffer = new StringBuffer();
    for(int i = 0; i < s.length(); i++)
    {
      int j = s.charAt(i);
      if(j != 32)
        stringbuffer.append((char)j);
    }
    return new String(stringbuffer);
  }
  public void run()
  {
    pos = 0;
    for(int i = 0; display != null; i = (i + 1) % 8)
    {
      done = false;
      for(int j = 0; j <= 10; j++)
      {
        refresh(j, i);
        try
        {
          Thread.sleep(speed);
        }
        catch(Exception _ex) { }
      }
      done = true;
      try
      {
        Thread.sleep(delay);
      }
      catch(Exception _ex) { }
      pos = (pos + 1) % all_news.size();
    }
  }
  public void start()
  {
    if(display == null)
    {
      display = new Thread(this);
      display.start();
    }
  }
  public void stop()
  {
    display = null;
  }
  public Color get_color(String s)
  {
    Integer integer = null;
    Integer integer1 = null;
    Integer integer2 = null;
    try
    {
      String s1 = getParameter(s);
      StringTokenizer stringtokenizer = new StringTokenizer(s1, ",");
      if(stringtokenizer.hasMoreTokens())
        integer = new Integer(remove_space(stringtokenizer.nextToken()));
      if(stringtokenizer.hasMoreTokens())
        integer1 = new Integer(remove_space(stringtokenizer.nextToken()));
      if(stringtokenizer.hasMoreTokens())
        integer2 = new Integer(remove_space(stringtokenizer.nextToken()));
      Color color = new Color(integer.intValue(), integer1.intValue(), integer2.intValue());
      return color;
    }
    catch(Exception _ex)
    {
      return null;
    }
  }
  public Font get_font(String s)
  {
    try
    {
      String s1 = getParameter(s);
      StringTokenizer stringtokenizer = new StringTokenizer(s1, ",");
      String s2 = null;
      String s3 = null;
      Integer integer = null;
      if(stringtokenizer.hasMoreTokens())
        s2 = new String(remove_space(stringtokenizer.nextToken()));
      if(stringtokenizer.hasMoreTokens())
        s3 = new String(remove_space(stringtokenizer.nextToken()));
      if(stringtokenizer.hasMoreTokens())
        integer = new Integer(remove_space(stringtokenizer.nextToken()));
      byte byte0;
      if(s3.equals("BOLD"))
        byte0 = 1;
      else
      if(s3.equals("ITALIC"))
        byte0 = 2;
      else
        byte0 = 0;
      Font font = new Font(s2, byte0, integer.intValue());
      return font;
    }
    catch(Exception _ex)
    {
      return null;
    }
  }
  public Vector parse_lines(Vector vector)
  {
    d = size();
    Vector vector1 = new Vector();
    int i = 0;
    int j = txtfont.getSize();
    int _tmp = d.height / j;
    fm = getToolkit().getFontMetrics(txtfont);
    StringBuffer stringbuffer = new StringBuffer();
    for(; i < vector.size(); i++)
    {
      String s = (String)vector.elementAt(i);
      stringbuffer.append(s);
      int k = fm.stringWidth(stringbuffer.toString());
      int l = -1;
      if(i < vector.size() - 1)
      {
        String s2 = (String)vector.elementAt(i + 1);
        StringBuffer stringbuffer1 = new StringBuffer(stringbuffer.toString());
        stringbuffer1.append(" ");
        stringbuffer1.append(s2);
        l = fm.stringWidth(stringbuffer1.toString());
      }
      if(k <= d.width - 8 && l >= d.width - 8 && i < vector.size())
      {
        vector1.addElement(new String(stringbuffer));
        stringbuffer = new StringBuffer();
        continue;
      }
      if(k <= d.width - 8 && i == vector.size() - 1)
      {
        vector1.addElement(new String(stringbuffer));
        stringbuffer = new StringBuffer();
        break;
      }
      if(k >= d.width - 8)
      {
        boolean flag = false;
        String s1 = new String(stringbuffer);
        for(int j1 = s1.length() - 1; j1 >= 0; j1--)
        {
          String s3 = s1.substring(0, j1);
          int i1 = fm.stringWidth(s3);
          if(i1 > d.width - 8)
            continue;
          vector1.addElement(s3 + "-");
          stringbuffer = new StringBuffer(s1.substring(j1));
          stringbuffer.append(" ");
          break;
        }
      } else
      {
        stringbuffer.append(" ");
      }
    }
    return vector1;
  }
  public message()
  {
    select_index = -1;
    all_urls = new Vector();
    all_news = new Vector();
    all_caps = new Vector();
    all_rects = new Vector();
    back_rects = new Vector();
    news_group = new Vector();
    legal = true;
    cap_fgcolor = Color.red;
    capfont = new Font("serif", 0, 22);
    bgcolor = new Color(255, 255, 255);
    fgcolor = Color.black;
    txtfont = new Font("serif", 0, 14);
    bdcolor = Color.red;
    mocolor = Color.pink;
    speed = 10;
    delay = 2000;
    window = "_self";
    mouse_in = false;
    done = true;
  }
}
```

