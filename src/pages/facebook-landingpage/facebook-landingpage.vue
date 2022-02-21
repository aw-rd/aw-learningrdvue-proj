<style scoped lang="scss" src="./facebook-landingpage.scss"></style>
<script lang="ts" src="./facebook-landingpage.ts"></script>

<template>
  <div class="facebook-landingpage">
    <div class="main-pane grid grid-cols-2">
      <div id="logo-pane" class="logo-pane">
        <img
          src="https://static.xx.fbcdn.net/rsrc.php/y8/r/dF5SId3UHWd.svg"
          class="[ logo ]"
        />
        <h1 class="call-to-action">
          Connect with friends and the world <br />around you on Facebook.
        </h1>
      </div>

      <div class="pos-left column-2">
        <div class="login-panel shadow-lg">
          <form>
            <input
              type="text"
              class="inputtext fb-fancy-textbox"
              name="email"
              id="email"
              data-testid="royal_email"
              placeholder="Email or phone number"
              autofocus="1"
              aria-label="Email or phone number"
            />
            <br />
            <input
              type="text"
              class="inputtext fb-fancy-textbox"
              name="password"
              id="password"
              data-testid="royal_email"
              placeholder="Password"
              autofocus="1"
              aria-label="Password"
            />
            <div>
              <button
                value="1"
                class="login-btn-blue"
                name="login"
                data-testid="royal_login_button"
                type="submit"
                id="fb-btn"
              >
                Log In
              </button>
            </div>
            <div class="forgot-btn">
              <a href="#"> Forgot password?</a>
            </div>
            <div class="separator"></div>
            <div class="btn-bottle-green">
              <a role="button" class="btn-bottle-green" href="#" rel="async"
                >Create new account</a
              >
            </div>
          </form>
        </div>
        <div class="create-page mx-10">
          <a href="#" class="font-bold">Create a Page</a>
          for a celebrity, brand or business.
        </div>
      </div>
    </div>
    <div class="grid grid-cols-1 main-footer md:container">
      <div class="footer-main md:container md:mx-auto">
        <ul class="uiList localeSelectorList" data-nocookies="1">
          <li>English (US)</li>
          <li>
            <a
              dir="ltr"
              href="https://fr-fr.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("fr_FR", "en_US", "https:\/\/fr-fr.facebook.com\/", "www_list_selector", 0); return false;'
              title="French (France)"
              >Français (France)</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://es-la.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("es_LA", "en_US", "https:\/\/es-la.facebook.com\/", "www_list_selector", 1); return false;'
              title="Spanish"
              >Español</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://id-id.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("id_ID", "en_US", "https:\/\/id-id.facebook.com\/", "www_list_selector", 2); return false;'
              title="Indonesian"
              >Bahasa Indonesia</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://it-it.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("it_IT", "en_US", "https:\/\/it-it.facebook.com\/", "www_list_selector", 3); return false;'
              title="Italian"
              >Italiano</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://de-de.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("de_DE", "en_US", "https:\/\/de-de.facebook.com\/", "www_list_selector", 4); return false;'
              title="German"
              >Deutsch</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://pt-br.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("pt_BR", "en_US", "https:\/\/pt-br.facebook.com\/", "www_list_selector", 5); return false;'
              title="Portuguese (Brazil)"
              >Português (Brasil)</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://zh-cn.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("zh_CN", "en_US", "https:\/\/zh-cn.facebook.com\/", "www_list_selector", 6); return false;'
              title="Simplified Chinese (China)"
              >中文(简体)</a
            >
          </li>
          <li>
            <a
              dir="rtl"
              href="https://ar-ar.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("ar_AR", "en_US", "https:\/\/ar-ar.facebook.com\/", "www_list_selector", 7); return false;'
              title="Arabic"
              >العربية</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://hi-in.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("hi_IN", "en_US", "https:\/\/hi-in.facebook.com\/", "www_list_selector", 8); return false;'
              title="Hindi"
              >हिन्दी</a
            >
          </li>
          <li>
            <a
              dir="ltr"
              href="https://ja-jp.facebook.com/"
              onclick='require("IntlUtils").setCookieLocale("ja_JP", "en_US", "https:\/\/ja-jp.facebook.com\/", "www_list_selector", 9); return false;'
              title="Japanese"
              >日本語</a
            >
          </li>
          <li>
            <a
              role="button"
              class="_42ft _4jy0 _517i _517h _51sy"
              rel="dialog"
              ajaxify="/settings/language/language/?uri=https%3A%2F%2Fja-jp.facebook.com%2F&amp;source=www_list_selector_more"
              href="#"
              title="Show more languages"
              ><i class="img sp_gMujFo71RwJ sx_25f620"></i
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>