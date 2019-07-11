unit Main;

interface

uses
  System.SysUtils, System.Types, System.UITypes, System.Classes, System.Variants,
  FMX.Types, FMX.Controls, FMX.Forms, FMX.Graphics, FMX.Dialogs, FMX.Objects, OpenViewUrl;

type
  TForm1 = class(TForm)
    Image1: TImage;
    procedure Image1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.fmx}

procedure TForm1.Image1Click(Sender: TObject);
begin
 try
   OpenViewUrl.OpenURL('fb://page/1662433320739229', True);
   {fb://profile/ProfileID} {Show Profile of People}
 except
   launchBrowser('https://www.facebook.com/WeClick.Digital/');
   {If Facebook App not installed then open the WebBrowser of the Phone and
   navigate to the page}
 end;
end;

end.
