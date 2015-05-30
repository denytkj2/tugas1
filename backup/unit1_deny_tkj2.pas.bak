unit unit1_deny_tkj2;

{$mode objfpc}{$H+}

interface

uses
  Classes, SysUtils, FileUtil, Forms, Controls, Graphics, Dialogs, StdCtrls;

type

  { TTugas_1 }

  TTugas_1 = class(TForm)
    Tentang: TCheckBox;
    Tekan: TButton;
    Sisipan: TLabel;
    Masukan: TEdit;
    procedure TekanClick(Sender: TObject);
    procedure TentangChange(Sender: TObject);
  private
    { private declarations }
  public
    { public declarations }
  end;

var
  Tugas_1: TTugas_1;

implementation

{$R *.lfm}

{ TTugas_1 }

procedure TTugas_1.TekanClick(Sender: TObject);
begin
  ShowMessage (Masukan.text) ;
end;

procedure TTugas_1.TentangChange(Sender: TObject);
begin
  if MessageDlg('Konfirmasi', 'Anda yakin untuk keluar?', mtConfirmation,
   [mbYes, mbNo],0) = mrYes
  then Application.terminate;
  ShowMessage ('Program ini dibuat oleh deny_tkj2') ;
end;

end.

