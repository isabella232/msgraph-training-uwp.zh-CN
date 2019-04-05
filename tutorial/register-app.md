<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="d8f64-101">在本练习中, 你将使用 azure Active Directory 管理中心创建新的 azure AD native 应用程序。</span><span class="sxs-lookup"><span data-stu-id="d8f64-101">In this exercise you will create a new Azure AD native application using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="d8f64-102">打开浏览器并导航到[Azure Active Directory 管理中心](https://aad.portal.azure.com), 并使用**个人帐户**(亦称为 "Microsoft 帐户") 或**工作或学校帐户**进行登录。</span><span class="sxs-lookup"><span data-stu-id="d8f64-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com) and login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="d8f64-103">在左侧导航栏中选择 " **Azure Active Directory** ", 然后选择 "**管理**" 下的 "**应用注册 (预览)** "。</span><span class="sxs-lookup"><span data-stu-id="d8f64-103">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations (Preview)** under **Manage**.</span></span>

    ![<span data-ttu-id="d8f64-104">应用注册的屏幕截图</span><span class="sxs-lookup"><span data-stu-id="d8f64-104">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="d8f64-105">选择 "**新建注册**"。</span><span class="sxs-lookup"><span data-stu-id="d8f64-105">Select **New registration**.</span></span> <span data-ttu-id="d8f64-106">在 "**注册应用程序**" 页上, 按如下所示设置值。</span><span class="sxs-lookup"><span data-stu-id="d8f64-106">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="d8f64-107">将**名称**设置`UWP Graph Tutorial`为。</span><span class="sxs-lookup"><span data-stu-id="d8f64-107">Set **Name** to `UWP Graph Tutorial`.</span></span>
    - <span data-ttu-id="d8f64-108">将**支持的帐户类型**设置为**任何组织目录和个人 Microsoft 帐户中的帐户**。</span><span class="sxs-lookup"><span data-stu-id="d8f64-108">Set **Supported account types** to **Accounts in any organizational directory and personal Microsoft accounts**.</span></span>
    - <span data-ttu-id="d8f64-109">将**重定向 URI**留空。</span><span class="sxs-lookup"><span data-stu-id="d8f64-109">Leave **Redirect URI** empty.</span></span>

    !["注册应用程序" 页的屏幕截图](./images/aad-register-an-app.png)

1. <span data-ttu-id="d8f64-111">选择 "**注册**"。</span><span class="sxs-lookup"><span data-stu-id="d8f64-111">Choose **Register**.</span></span> <span data-ttu-id="d8f64-112">在**UWP Graph 教程**页上, 复制**应用程序 (客户端) ID**的值并保存它, 下一步将需要它。</span><span class="sxs-lookup"><span data-stu-id="d8f64-112">On the **UWP Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![新应用注册的应用程序 ID 的屏幕截图](./images/aad-application-id.png)

1. <span data-ttu-id="d8f64-114">选择 "**添加重定向 URI** " 链接。</span><span class="sxs-lookup"><span data-stu-id="d8f64-114">Select the **Add a Redirect URI** link.</span></span> <span data-ttu-id="d8f64-115">在 "**重定向 uri** " 页上, 找到 "**公共客户端 (移动、桌面)** " 部分的 "建议的重定向 uri" 部分。</span><span class="sxs-lookup"><span data-stu-id="d8f64-115">On the **Redirect URIs** page, locate the **Suggested Redirect URIs for public clients (mobile, desktop)** section.</span></span> <span data-ttu-id="d8f64-116">选择 URI `urn:ietf:wg:oauth:2.0:oob` , 然后选择 "**保存**"。</span><span class="sxs-lookup"><span data-stu-id="d8f64-116">Select the `urn:ietf:wg:oauth:2.0:oob` URI, then choose **Save**.</span></span>

    !["重定向 uri" 页的屏幕截图](./images/aad-redirect-uris.png)