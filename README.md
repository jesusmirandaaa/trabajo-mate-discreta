#include "FrmMenu.h"

using namespace System;
using namespace Windows::Forms;
using namespace Reticulas;

void main() {
    //Application::SetCompatibleTextRenderingDefault(false);
    Application::EnableVisualStyles();
    Application::Run(gcnew Reticulas::FrmMenu);
}

