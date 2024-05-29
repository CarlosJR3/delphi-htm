unit Unit1;

interface

uses
  Winapi.Windows, Winapi.Messages, System.SysUtils, System.Variants, System.Classes, Vcl.Graphics,
  Vcl.Controls, Vcl.Forms, Vcl.Dialogs;

type
  TForm1 = class(TForm)
    procedure FormCreate(Sender: TObject);
  private
    { Private declarations }
    procedure createDirectory;

  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.createDirectory;
var
 Patch : String;
begin
Patch := ExtractFilePath(ParamStr(0));
      if not DirectoryExists(Patch +'HTML') then
      CreateDir(Patch +'HTML');

      if not DirectoryExists(Patch +'HTML\assets') then
      CreateDir(Patch +'HTML\assets');

       if not DirectoryExists(Patch +'HTML\assets\animatecss') then
      CreateDir(Patch +'HTML\assets\animatecss');

       if not DirectoryExists(Patch +'HTML\assets\bootstrap') then
      CreateDir(Patch +'HTML\assets\bootstrap');

       if not DirectoryExists(Patch +'HTML\assets\dropdown') then
      CreateDir(Patch +'HTML\assets\dropdown');

       if not DirectoryExists(Patch +'HTML\assets\formoid') then
      CreateDir(Patch +'HTML\assets\formoid');

       if not DirectoryExists(Patch +'HTML\assets\gallery') then
      CreateDir(Patch +'HTML\assets\gallery');

       if not DirectoryExists(Patch +'HTML\assets\images') then
      CreateDir(Patch +'HTML\assets\images');

       if not DirectoryExists(Patch +'HTML\assets\imagesloaded') then
      CreateDir(Patch +'HTML\assets\imagesloaded');

       if not DirectoryExists(Patch +'HTML\assets\masonry') then
      CreateDir(Patch +'HTML\assets\masonry');

       if not DirectoryExists(Patch +'HTML\assets\mobirise') then
      CreateDir(Patch +'HTML\assets\mobirise');

       if not DirectoryExists(Patch +'HTML\assets\smoothscroll') then
      CreateDir(Patch +'HTML\assets\smoothscroll');

           if not DirectoryExists(Patch +'HTML\assets\socicon') then
      CreateDir(Patch +'HTML\assets\socicon');

       if not DirectoryExists(Patch +'HTML\assets\theme') then
      CreateDir(Patch +'HTML\assets\theme');

       if not DirectoryExists(Patch +'HTML\assets\web') then
      CreateDir(Patch +'HTML\assets\web');

       if not DirectoryExists(Patch +'HTML\assets\ytplayer') then
      CreateDir(Patch +'HTML\assets\ytplayer');
end;


procedure TForm1.FormCreate(Sender: TObject);
begin
           createDirectory;
end;

end.
